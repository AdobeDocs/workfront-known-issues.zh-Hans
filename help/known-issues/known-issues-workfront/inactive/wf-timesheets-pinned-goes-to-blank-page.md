---
title: “时间表：固定的时间表变为空白页面”
description: “当用户单击 Workfront 中原本要转到其时间表的大头针时，该大头针却会转到一个空白页面。有解决方法可用。”
hidefromtoc: true
feature: Timesheets
source-git-commit: 89eb14bfaccb517764af1711ca31e2926de63795
workflow-type: ht
source-wordcount: '123'
ht-degree: 100%

---


# 时间表：固定的时间表变为空白页面

当用户单击 Workfront 中原本要转到其时间表的大头针时，该大头针却会转到一个空白页面。

这是因为时间表的 URL 已改变。URL 末尾的 `/own` 不再是正确的 URL。如果用户固定了包含 `/own` 的 URL，则该大头针会指向空白页面。

**解决方法**

1. 取消固定时间表。
1. 从 URL 末尾移除 `/own` 
1. 重新固定时间表。

_首次报告于 2024 年 5 月 7 日。_

