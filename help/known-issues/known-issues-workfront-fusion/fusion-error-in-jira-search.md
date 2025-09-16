---
title: Workfront Fusion：Jira搜索模块返回错误
description: 旧版Jira连接器使用的搜索模块可能会导致错误。 有解决方法可用
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 2%

---


# Workfront Fusion：Jira搜索模块返回错误

>[!NOTE]
>
>此问题是由于Jira在其产品中所做的更改所致。

旧版Jira连接器使用的搜索模块可能会导致以下错误：

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

这是由于Jira方面的弃用。

请注意：

* 只有搜索模块受影响。 目前，Fusion连接器使用的其他Jira API端点不受此弃用的影响。

* 地理转出可能会导致不一致。 Atlassian正在区域范围内推出此更改，这意味着某些Jira云实例可能仍会临时支持旧端点。 这可能会导致环境之间的行为不一致。

**解决方法**

如果遇到此错误，您可以使用新连接器的搜索模块替换旧版Jira连接器的搜索模块。 请注意，新连接器允许您选择使用的API版本。 创建连接时，请确保在&#x200B;**API版本**&#x200B;字段中选择&#x200B;**V3**。

_首次报告于2025年9月15日。_

