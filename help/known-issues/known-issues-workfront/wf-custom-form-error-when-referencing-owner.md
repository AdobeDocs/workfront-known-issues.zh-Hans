---
title: '自定义表单：在计算字段中引用所有者时，出现“自定义表达式无效”消息'
description: '当用户将计算字段添加到问题级自定义表单并尝试添加任何对所有者的引用（如 `ownerID`）时，并未保存该字段，而用户看到以下消息：这是无效的自定义表达式，请重试。'
hidefromtoc: true
exl-id: 254f1fae-0784-4332-99a1-cc1895c50896
source-git-commit: d6935a9ad66633d64083f227def3b027349645b1
workflow-type: ht
source-wordcount: '135'
ht-degree: 100%

---

# 自定义表单：在计算字段中引用“[!UICONTROL 所有者]”时，出现“[!UICONTROL 自定义表达式无效]”消息

>[!NOTE]
>
>此问题已于 2023 年 3 月 9 日修复。

<!--
>[!NOTE]
>
>This issue was fixed on December 1, 2022.
-->

当用户将计算字段添加到问题级自定义表单并尝试添加任何对“[!UICONTROL 所有者]”的引用（如 `ownerID`）时，并未保存该字段，而用户看到以下消息：

&quot;[!UICONTROL 这是无效的自定义表达式，请重试。]&quot;

即使表达式有效，也会发生这种情况。

_首次报告于 2022 年 11 月 8 日。_
