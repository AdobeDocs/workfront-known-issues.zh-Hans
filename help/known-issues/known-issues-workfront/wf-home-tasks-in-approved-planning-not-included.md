---
title: “主页：项目中状态为“已批准”或“计划”的任务未包含在“我的任务”或“主页工作列表”中”
description: “项目中状态为“已批准”或“计划”的任务不会显示在主页中。 有变通方案可用。”
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 3%

---


# 主页：项目中状态为“已批准”或“计划”的任务未包含在“我的任务”或“主页工作列表”中

项目中状态为“已批准”或“计划”的任务不会显示在以下区域中：

* Classic主页：工作列表
* 新主页：我的任务小组件

这是因为处于这些状态的项目中的任务当前包含在2000项查询限制中，但是它们未显示在“我的任务”或“主页工作列表”中。 这可能会导致用户拥有的任务少于2000个，这些任务不可见。

**解决方法**

创建包含以下文本模式过滤器的自定义“工作总揽”报表：

当分配为AWAITING_ACCEPTION时，包括当前|批准的项目：

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

接受分配后，包括当前|已批准|计划项目：

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
