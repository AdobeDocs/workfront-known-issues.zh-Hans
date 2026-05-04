---
title: Workfront Fusion：Jira 搜索模块返回错误
description: 旧版 Jira 连接器中使用的搜索模块可能会返回错误。 有解决方法可用
feature: Workfront Fusion
exl-id: 9502ffb3-f287-47b2-9b35-1a906345e924
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 100%

---

# Workfront Fusion：Jira 搜索模块返回错误

>[!NOTE]
>
>此问题是由于 Jira 在其产品中进行的更改所致。

旧版 Jira 连接器中使用的搜索模块可能会返回以下错误：

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

这是由于 Jira 端弃用了相关功能导致的。

注意：

* 仅搜索模块受到影响。 目前，Fusion 连接器使用的其他 Jira API 端点不受此弃用影响。

* 按地区分阶段发布可能会导致行为不一致。 Atlassian 正在按地区逐步推出此更改，这意味着部分 Jira Cloud 实例可能仍会暂时支持旧端点。 这可能会导致不同环境中的行为不一致。

**解决方法**

如果遇到此错误，可将旧版 Jira 连接器的搜索模块替换为新版连接器的搜索模块。 请注意，新版连接器允许您选择所使用的 API 版本。 在创建连接时，请务必在 **API 版本**&#x200B;字段中选择 **V3**。

_首次报告时间：2025 年 9 月 15 日。_
