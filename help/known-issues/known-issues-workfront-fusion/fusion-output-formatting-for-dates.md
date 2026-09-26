---
title: Workfront Fusion：日期的输出格式
description: 在将日期作为字符串输出时，可将日期作为 UTC 或 ISO 字符串输出。 这取决于映射面板中的逻辑。
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%
---
# Workfront Fusion：日期的输出格式

在将日期作为字符串输出时，可将日期作为 UTC 或 ISO 字符串输出。 这取决于映射面板中的逻辑：

* 如果函数中的日期连接到字符串，则字符串将以 **UTC** 格式输出。
* 如果日期未在函数内连接，它将作为 **ISO 字符串**&#x200B;输出。

客户应使用 `toString`（对于 ISO）或 `formatDate` 函数来确保输出采用其所需的格式。
