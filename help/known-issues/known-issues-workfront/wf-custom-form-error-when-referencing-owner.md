---
title: '自定义表单：在计算字段中引用所有者时，出现“自定义表达式无效”消息'
description: '当用户将计算字段添加到问题级自定义表单并尝试添加任何对所有者的引用（如 `ownerID`）时，并未保存该字段，而用户看到以下消息：这是无效的自定义表达式，请重试。'
hidefromtoc: true
exl-id: 254f1fae-0784-4332-99a1-cc1895c50896
source-git-commit: db076ee06c75e2d8a185b539ef54779aa0ec0630
workflow-type: ht
source-wordcount: '157'
ht-degree: 100%

---

# 自定义表单：在计算字段中引用“[!UICONTROL 所有者]”时，出现“[!UICONTROL 自定义表达式无效]”消息

>[!NOTE]
>
>产品团队目前正在评估此问题的解决方案，这可能需要产品增强功能。 产品增强功能在“产品公告”中而非“维护更新”中传送。

<!--
>[!NOTE]
>
>This issue was fixed on December 1, 2022.
-->

当用户将计算字段添加到问题级自定义表单并尝试添加任何对“[!UICONTROL 所有者]”的引用（如 `ownerID`）时，并未保存该字段，而用户看到以下消息：

&quot;[!UICONTROL 这是无效的自定义表达式，请重试。]&quot;

即使表达式有效，也会发生这种情况。

_首次报告于 2022 年 11 月 8 日。_
