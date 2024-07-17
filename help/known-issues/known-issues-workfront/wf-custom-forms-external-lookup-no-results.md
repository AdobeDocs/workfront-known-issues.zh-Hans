---
title: “自定义表单：外部查找字段不会返回结果”
description: 当外部查找字段引用只选择了一个值的多选字段时，该字段不会返回该值。
hidefromtoc: true
feature: Custom Forms
exl-id: b65c8870-e915-4ca5-a93b-5431440f9140
source-git-commit: dbc4e4ecd9e7b2a6d01b43f46a3c2fd128c1d1dc
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 100%

---

# 自定义表单：外部查找字段不会返回结果

>[!NOTE]
>
>该问题已于 2024 年 4 月 18 日修复。

当外部查找字段引用只选择了一个值的多选字段时，该字段不会返回该值。

例如，如果外部查找字段引用了同时选择了“红色”和“蓝色”值的多选字段，则该字段会按预期运行。如果该字段仅选择了“红色”，则外部查找字段不会返回任何值。

_首次报告于 2024 年 4 月 2 日。_
