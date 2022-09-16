---
title: “项目：从标题中删除项目所有者时出错
description: 当用户尝试从项目标题中删除项目所有者时，不会删除项目所有者，并且用户会看到一条错误消息。
hidefromtoc: true
exl-id: 3a995df4-5d6a-44e4-a644-997931c044bf
source-git-commit: 7570b2a560505d66e0e83656c9a601226998c11c
workflow-type: tm+mt
source-wordcount: '97'
ht-degree: 0%

---

# 项目：删除 [!UICONTROL 项目所有者] 从标题

>[!NOTE]
>
>此问题已于2022年9月9日修复。

当用户尝试删除 [!UICONTROL 项目所有者] 在项目标题中， [!UICONTROL 项目所有者] 未删除，且用户看到以下错误消息：

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**解决方法**

删除[!UICONTROL  项目所有者] 的 [!UICONTROL 详细信息] 的上界。

_第一次报告是在2022年8月9日。_
