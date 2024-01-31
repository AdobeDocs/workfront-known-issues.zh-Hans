---
title: “Workfront Fusion：输出日期的格式”
description: “当日期输出为字符串时，日期可以输出为UTC或ISO字符串。 这取决于映射面板中的逻辑。”
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Workfront Fusion：输出日期的格式

当日期输出为字符串时，日期可以输出为UTC或ISO字符串。 这取决于映射面板中的逻辑：

* 如果将函数中的某个日期连接到字符串，则会将该字符串输出到 **UTC** 格式。
* 如果日期未联接到函数中，它将输出为 **ISO字符串**.

客户应使用 `toString` （对于ISO）或 `formatDate` 函数以确保输出符合所需的格式。
