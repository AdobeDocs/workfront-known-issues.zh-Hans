---
title: 'Workfront：ZScaler设置可能会导致性能降低'
description: 默认情况下，ZScaler的Web服务使用http/1.1，这会导致Workfront中的性能降低。
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 1%

---

# Workfront： ZScaler设置可能会导致性能降低

>[!NOTE]
>
>这是ZScaler的问题，Workfront不会修复此问题。

默认情况下，ZScaler的Web服务使用`http/1.1`，这会导致Workfront中的性能降低。

**解决方法**

将ZScaler软件配置为使用`http/2`。 无法在Workfront中配置此设置。

您可以在ZScaler文档中找到有关`http/2`的信息。

_首次报告于2024年11月18日。_
