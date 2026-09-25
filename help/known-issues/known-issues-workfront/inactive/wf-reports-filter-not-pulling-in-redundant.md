---
title: 报告：报告筛选条件未返回预期结果
description: 报告中的筛选条件可能不会返回所有预期结果。 有解决方法可用。
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
    internal-label: Reports and dashboards
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 100%
---
# 报告：报告筛选条件未返回预期结果

>[!NOTE]
>
>此问题已关闭。

报告中的筛选条件可能不会返回所有预期结果。

当将筛选条件配置为返回具有特定条件的结果，并且包含返回同一条件子集的结果的 OR 规则时，可能会发生这种情况。

**解决方法**

确保筛选条件的 OR 块不包含相同的评估标准。

_首次报告于 2024 年 3 月 11 日。_
