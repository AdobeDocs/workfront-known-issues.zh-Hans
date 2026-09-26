---
title: 自定义表单：设置计算字段时出现“糟糕”错误
description: 当用户在自定义表单中创建或编辑计算字段并在计算字段的表达式中包含自定义字段时，表达式被视为无效。 ‘保存’按钮已禁用，并且用户无法退出自定义字段。 此外，用户会在该字段下方看到‘糟糕’消息。
feature: Custom Forms
exl-id: e499c680-2fdf-40cb-a1fa-b0d4ae799ad2
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 94%
---
# 自定义表单：设置计算字段时出现“[!UICONTROL 糟糕]”错误

<!--Requested: Do not delete without approval from Alex Beach-->

>[!NOTE]
>
>此问题已于 2023 年 1 月 12 日修复

当用户在自定义表单中创建或编辑计算字段并在计算字段的表达式中包含自定义字段时，表达式被视为无效。 [!UICONTROL 保存]按钮已禁用，并且用户无法退出自定义字段。 此外，用户会在该字段下方看到以下消息：

“[!UICONTROL 糟糕！ 出现问题。 请联系 Workfront，以便我们找出错误并加以修复。]”

从表达式中移除自定义字段可让用户保存并退出该字段。

_首次报告于 2022 年 10 月 11 日。_
