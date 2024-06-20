---
title: "新主页：构件筛选条件和分组默认值不遵循布局模板"
description: 当用户在新主页体验中查看我的项目、我的任务或我的问题构件时，该构件的默认筛选条件和分组不是分配给该用户的布局模板中的默认设置。
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: ht
source-wordcount: '191'
ht-degree: 100%

---

# 新[!UICONTROL 主页]：构件筛选条件和分组默认值不遵循布局模板

>[!NOTE]
>
>此问题已关闭，因为它已按设计运行。

当用户在新[!UICONTROL 主页]体验中查看[!UICONTROL 我的项目]、[!UICONTROL 我的任务]或[!UICONTROL 我的问题]构件时，该构件的默认筛选条件和分组不是分配给该用户的布局模板中的默认设置。

**解决方法**：

使用“新主页”时，请务必记住用户设置（偏好设置）的优先级。因此，如果使用布局模板为特定构件设置默认筛选条件或分组，由于现有的用户偏好，可能无法立即生效。要应用新的筛选条件或分组，您或用户可能需要重置偏好设置。这可以通过在 URL 中添加 `/resetUser` 来实现。

_首次报告于 2024 年 1 月 3 日。_
