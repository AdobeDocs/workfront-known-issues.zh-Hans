---
title: '自定义表单：无法在模板任务上批量添加或批量删除自定义表单'
description: 如果用户尝试在模板任务上批量添加或批量删除某个自定义表单，并不添加或删除该表单，并且出现一条错误。
hidefromtoc: true
feature: Custom Forms
exl-id: e9014f67-2098-46e4-a301-6a742a0c2ddb
source-git-commit: d3d6529fea8f2d020f4920ee5b2bda723f348cc2
workflow-type: ht
source-wordcount: '159'
ht-degree: 100%

---

# 自定义表单：无法在模板任务上批量添加或批量删除自定义表单

>[!NOTE]
>
>此问题已于 2024 年 1 月 18 日修复。

如果用户尝试在模板任务上批量添加或批量删除某个自定义表单，并不添加或删除该表单，并且出现以下错误：

[!UICONTROL 让我们再试一次。无效参数：templateID 值 &quot;XXXXXXXXXXXXXXXX&quot;]

如果用户找到具有指定 GUID 的模板，然后尝试在模板任务的剩余部分添加或删除自定义表单，则使用另一个 templateID 将重现该错误。

可在单个模板任务上添加或删除自定义表单。此错误仅适用于批量添加或删除。

_首次报告于 2023 年 11 月 10 日。_
