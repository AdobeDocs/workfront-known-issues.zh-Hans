---
title: “自定义表单：无法在模板任务中批量添加或批量删除自定义表单”
description: “如果用户尝试在模板任务上批量添加或批量移除自定义表单，则不会添加或删除该表单，并且用户会看到错误消息。”
hidefromtoc: true
feature: Custom Forms
source-git-commit: 41df80641db82b225753338d8564e12b90566c40
workflow-type: tm+mt
source-wordcount: '153'
ht-degree: 5%

---


# 自定义表单：无法在模板任务中批量添加或批量删除自定义表单

如果用户尝试在模板任务上批量添加或批量移除自定义表单，则不会添加或删除该表单，并且用户会看到以下错误消息：

[!UICONTROL 让我们再试一次。 无效参数：templateID值“XXXXXXXXXXXXXXXX”]

如果用户使用指定的GUID找到模板，然后尝试在其余模板任务中添加或删除自定义表单，则使用其他templateID将重新发生该错误。

可以在单个模板任务中添加或删除自定义表单。 此错误仅适用于批量添加或删除。

_首次报告于 2023 年 11 月 10 日。_
