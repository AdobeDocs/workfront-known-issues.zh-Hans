---
title: "主页：“我的任务”或“主页工作列表”中不含处于“已批准”或“正在规划”状态的项目中的任务"
description: "“主页”中不显示状态为“已批准”或“正在规划”的项目中的任务。有变通方法可用。"
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: ht
source-wordcount: '166'
ht-degree: 100%

---


# 主页：“我的任务”或“主页工作列表”中不含处于“已批准”或“正在规划”状态的项目中的任务

以下区域中不显示状态为“已批准”或“正在规划”的项目中的任务：

* 经典主页：工作列表
* 新主页：“我的任务”构件

这是因为当前在 2000 项查询限制中包括处于这些状态的项目中的任务，但不在“我的任务”或“主页工作列表”中显示它们。这可能会造成任务少于 2000 个的用户看不到这些任务的情况。

**变通方法**

创建一个自定义任务报告，其中包括以下文本模式过滤器：

当任务处于 AWAITING_ACCEPTANCE 状态时，包括 CURRENT|APPROVED 项目：

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

当任务处于 ACCEPTED 状态时，包括 CURRENT|APPROVED|PLANNING 项目：

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_首次报告于 2023 年 11 月 6 日。_
