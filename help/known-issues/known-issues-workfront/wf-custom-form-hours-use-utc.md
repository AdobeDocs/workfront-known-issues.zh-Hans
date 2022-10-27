---
title: “自定义表单：计算字段中的HOUR函数使用UTC”
description: “当计算字段包含HOUR函数时，该函数会根据UTC而不是预期时区返回值。 因此，任何基于HOUR值的计算都不正确。”
hidefromtoc: true
source-git-commit: 8f04dc85caf0019001913bb4762c924109516a96
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 4%

---


# 自定义表单： [!UICONTROL 小时] 函数使用UTC

>[!NOTE]
>
>此问题已于2022年10月27日修复。

当计算字段包含 [!UICONTROL 小时] 函数时，该函数会根据UTC而不是预期时区返回值。 因此，任何基于HOUR值的计算都不正确。

_首次报告于 2022 年 10 月 17 日。_

