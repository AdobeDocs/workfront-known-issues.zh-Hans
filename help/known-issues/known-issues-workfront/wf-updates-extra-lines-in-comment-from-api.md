---
title: "更新：通过 API 或 Workfront Fusion 发表的评论中行数过多"
description: "当用户通过 API 或 Workfront Fusion 提交评论时，“更新”区域中显示的评论行数过多。有时行数过多，以致于用户必须向下滚动才能看到评论内容。"
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 6d87394383aaf54385163729f85ea065588967c9
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 100%

---


# 更新：通过 API 或 [!DNL Workfront Fusion] 发表的评论中行数过多

>[!NOTE]
>
>此问题已于 2023 年 11 月 16 日修复。

当用户通过 API 或 [!DNL Workfront Fusion] 提交评论时，“更新”区域中显示的评论行数过多。有时行数过多，以致于用户必须向下滚动才能看到评论内容。

已在新的评论体验中报告了此问题。

**变通方法**

此问题是在评论中提交的 HTML 中有空格或换行所致。

为了避免出现此问题，请确保所有 HTML 都在一行上，并且 HTML 元素之间没有空格或换行。

要查看受影响的评论而不显示多余的行，请切换到经典评论体验。

_首次报告于 2023 年 10 月 27 日。_
