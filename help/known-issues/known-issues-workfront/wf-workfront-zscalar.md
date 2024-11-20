---
title: “Workfront：ZScalar设置可能会导致性能降低”
description: “默认情况下，ZScalar的Web服务使用http/1.1，这会导致Workfront中的性能降低。”
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 1%

---


# Workfront： ZScalar设置可能会导致性能降低

>[!NOTE]
>
>这是ZScalar的一个问题，Workfront不会修复此问题。

默认情况下，ZScalar的Web服务使用`http/1.1`，这会导致Workfront中的性能降低。

**解决方法**

配置ZScalar软件以使用`http/2`。 无法在Workfront中配置此设置。

您可以在ZScalar文档中找到有关`http/2`的信息。

_首次报告于2024年11月18日。_
