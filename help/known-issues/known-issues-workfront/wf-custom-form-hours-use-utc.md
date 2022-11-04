---
title: “自定义表单：计算字段中的 HOUR 函数使用 UTC”
description: “当计算字段包含 HOUR 函数时，该函数根据 UTC 而不是预期时区返回值。因此，任何基于 HOUR 值的计算均不正确。”
hidefromtoc: true
source-git-commit: a681d8afd4bcf1ddfccf192871442e63dae1b2c3
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 93%

---


# 自定义表单：计算字段中的 [!UICONTROL HOUR] 函数使用 UTC

>[!NOTE]
>
>此问题已于2022年11月3日修复。

当计算字段包含 [!UICONTROL HOUR] 函数时，该函数根据 UTC 而不是预期时区返回值。因此，任何基于 HOUR 值的计算均不正确。

_首次报告于 2022 年 10 月 17 日。_

