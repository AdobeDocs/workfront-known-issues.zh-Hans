---
title: Workfront：ZScaler 设置可能会导致性能下降
description: ZScaler 的 Web 服务默认使用 http/1.1，这会导致 Workfront 的性能下降。
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
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
source-wordcount: '83'
ht-degree: 100%
---
# Workfront：ZScaler 设置可能会导致性能下降

>[!NOTE]
>
>这是 ZScaler 的问题，Workfront 不会修复。

ZScaler 的 Web 服务默认使用 `http/1.1`，这会导致 Workfront 的性能下降。

**解决方法**

配置您的 ZScaler 软件以供使用 `http/2`。 这无法在 Workfront 中配置。

您可以在 ZScaler 文档中找到有关 `http/2` 的信息。

_首次报告于 2024 年 11 月 18 日。_
