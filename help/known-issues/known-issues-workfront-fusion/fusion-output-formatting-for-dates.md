---
title: “Workfront Fusion：日期的输出格式”
description: “在将日期作为字符串输出时，可将日期作为 UTC 或 ISO 字符串输出。这取决于映射面板中的逻辑。”
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---


# Workfront Fusion：日期的输出格式

在将日期作为字符串输出时，可将日期作为 UTC 或 ISO 字符串输出。这取决于映射面板中的逻辑：

* 如果函数中的日期连接到字符串，则字符串将以 **UTC** 格式输出。
* 如果日期未在函数内连接，它将作为 **ISO 字符串**&#x200B;输出。

客户应使用 `toString`（对于 ISO）或 `formatDate` 函数来确保输出采用其所需的格式。
