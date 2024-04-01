---
title: 'Workfront Fusion：来自Workfront模块的200响应出现RuntimeError'
description: Workfront模块可以返回“RuntimeError [200]”响应。 200 意味着响应成功，而错误表明请求失败。
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: 58d9dedba766417d68892c94d18d0ee4e9c03b51
workflow-type: tm+mt
source-wordcount: '96'
ht-degree: 73%

---

# Workfront Fusion：RuntimeError，显示来自 Workfront 模块的 200 响应

>[!NOTE]
>
>此问题已于2024年3月28日修复。

Workfront 模块可以返回 `RuntimeError [200]` 响应。200 意味着响应成功，而错误表明请求失败。

如果响应非常长，则可能会发生此情况。数据返回到 Fusion，但无法由 Fusion 处理。

_首次报告于 2024 年 1 月 3 日。_
