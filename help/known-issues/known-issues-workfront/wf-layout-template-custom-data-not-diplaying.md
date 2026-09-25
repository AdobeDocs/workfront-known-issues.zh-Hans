---
title: 布局模板：通过布局模板添加到任务摘要时不显示自定义数据字段
description: 当管理员通过布局模板将自定义数据字段添加到任务摘要部分时，对于查看任务摘要部分的用户来说，字段显示为空。
feature: System Setup and Administration
exl-id: f37ecfc5-30b9-4fe2-9e76-a97be0ae969f
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 100%
---
# 布局模板：通过布局模板添加到任务摘要时不显示自定义数据字段

>[!NOTE]
>
>此问题已关闭，因为它已按预期运行。 请参阅下面的解决方法。

当管理员通过布局模板将自定义数据字段添加到任务摘要部分时，对于查看任务摘要部分的用户来说，该字段显示为空。

**解决方法**

避免在自定义字段名称中 使用句点“.”，以避免此问题。 您可以重新为“摘要”部分中的自定义字段赋予标签，并根据需要包含句点。

_首次报告于 2024 年 10 月 2 日。_
