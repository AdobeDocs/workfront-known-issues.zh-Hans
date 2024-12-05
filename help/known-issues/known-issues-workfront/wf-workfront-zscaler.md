---
title: Workfront：ZScaler 设置可能会导致性能下降
description: ZScaler 的 Web 服务默认使用 http/1.1，这会导致 Workfront 的性能下降。
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: ht
source-wordcount: '81'
ht-degree: 100%

---

# Workfront：ZScaler 设置可能会导致性能下降

>[!NOTE]
>
>这是 ZScaler 的问题，Workfront 不会修复。

ZScaler 的 Web 服务默认使用 `http/1.1`，这会导致 Workfront 的性能下降。

**解决方法**

配置您的 ZScaler 软件以供使用 `http/2`。这无法在 Workfront 中配置。

您可以在 ZScaler 文档中找到有关 `http/2` 的信息。

_首次报告于 2024 年 11 月 18 日。_
