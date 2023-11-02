---
title: “更新：通过API或Workfront Fusion所做的注释中有额外的行”
description: “当用户通过API或Workfront Fusion提交评论时，更新区域显示的评论显示额外的行。 有时，行数太多，用户必须向下滚动才能查看评论内容。”
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 1854e4a003722f1398c703dfba7bc23ef534f81f
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 8%

---


# 更新：通过API或进行的注释中存在额外的行 [!DNL Workfront Fusion]

当用户通过API或通过提交评论时 [!DNL Workfront Fusion]时，更新区域显示的注释会显示额外的行。 有时，注释行太多，用户必须向下滚动才能查看注释内容。

已在新的评论体验中报告了此问题。

**解决方法**

此问题由注释中提交的HTML中的空格或换行符引起。

要避免出现此问题，请确保所有HTML都位于一行中，HTML元素之间无空格或换行符。

要查看受影响的注释而不添加额外的行，请切换到传统的注释体验。

_首次报告于 2023 年 10 月 27 日。_
