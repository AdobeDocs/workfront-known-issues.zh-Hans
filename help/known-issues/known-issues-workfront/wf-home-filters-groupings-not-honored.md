---
title: '新主页：构件筛选器和分组默认值不遵循布局模板'
description: 当用户在新主页体验中查看我的项目、我的任务或我的问题小部件时，该小部件的默认筛选器和分组不是分配给该用户的布局模板中的默认设置。
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 36%

---

# 新[!UICONTROL 主页]：构件筛选条件和分组默认值不遵循布局模板

>[!NOTE]
>
>此问题已关闭，因为它已按设计运行。

当用户在新[!UICONTROL 主页]体验中查看[!UICONTROL 我的项目]、[!UICONTROL 我的任务]或[!UICONTROL 我的问题]构件时，该构件的默认筛选条件和分组不是分配给该用户的布局模板中的默认设置。

**解决方法**：

使用新主页时，切记用户设置（首选项）是优先选项。 因此，如果您使用布局模板为特定构件设置默认过滤器或分组，则由于现有用户首选项，该过滤器或分组可能不会立即生效。 要应用新的过滤器或分组，您或用户可能需要重置首选项。 这可以通过附加来完成 `/resetUser` 到您的URL。

_首次报告于 2024 年 1 月 3 日。_
