---
title: 时间表：固定的时间表变为空白页面
description: 当用户单击 Workfront 中原本要转到其时间表的大头针时，该大头针却会转到一个空白页面。 有解决方法可用。
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 100%
---
# 时间表：固定的时间表变为空白页面

<!--article live for workaround-->

当用户单击 Workfront 中原本要转到其时间表的大头针时，该大头针却会转到一个空白页面。

这是因为时间表的 URL 已改变。 URL 末尾的 `/own` 不再是正确的 URL。 如果用户固定了包含 `/own` 的 URL，则该大头针会指向空白页面。

**解决方法**

1. 取消固定时间表。
1. 从 URL 末尾移除 `/own`
1. 重新固定时间表。

_首次报告于 2024 年 5 月 7 日。_
