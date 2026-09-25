---
title: 审批：为不正确的天数设置了审批委派
description: 当用户安排”个人休息时间“并委派响应审批时，审批委派可能包括安排的休息时间之前或之后的天数。
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: b04e3dc0-3a59-45b1-aa02-b0b6d5f87eff
    internal-label: Approvals
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 100%
---
# 审批：为不正确的天数设置了审批委派

<!--Live for workaround-->

>[!NOTE]
>
>此问题已关闭，因为它现在不构成问题。

当用户安排”个人休息时间“并委派响应审批时，审批委派可能包括安排的休息时间之前或之后的天数。

**解决方法**

这种差异是由于用户档案中的时区与用户分配的时间表的时区之间的差异造成的。

我们建议为用户工作的每个时区创建一个唯一的时间表，并将每个用户分配到与其用户档案中的时区匹配的时间表。

_首次报告于 2022 年 3 月 24 日。_
