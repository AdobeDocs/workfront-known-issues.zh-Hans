---
title: “自定义表单：如果字段名称包含引号或撇号，则无法在计算中使用字段”
description: “当用户创建计算字段表达式并尝试包含名称带有撇号或引号的预输入字段时，计算不被接受，并且用户看到消息：这是一个无效的自定义表达式，请尝试再次。”
hidefromtoc: true
source-git-commit: 254339d1baa9d8d7825e851aeafc9b27b1a1b669
workflow-type: ht
source-wordcount: '176'
ht-degree: 100%

---


# 自定义表单：如果字段名称包含撇号或引号，则无法在计算中使用字段

>[!NOTE]
>
>产品团队目前正在评估此问题的解决方案，这可能需要产品增强功能。 产品增强功能在“产品公告”中而非“维护更新”中传送。

当用户创建计算字段表达式并尝试包含名称带有 `'` 或 `"` 的预输入字段时，计算不被接受，并且用户看到消息“[!UICONTROL 这是一个无效的自定义表达式，请重试。]”

此问题仅存在于预输入字段中。 名称中带有 `'` 或 `"` 的文本字段可以毫无问题地用于计算字段表达式。

_首次报告于 2022 年 11 月 10 日。_

