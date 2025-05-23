---
title: 用户：在新用户上显示未决批准徽章
description: Workfront中的新用户可能显示在带有待审批徽章的用户列表中。 该徽章会持续存在超过几分钟，并在页面刷新时仍然存在。
hidefromtoc: true
feature: People Teams and Groups
source-git-commit: 9c46f9006fa25481a012619a16d627e16f23c15e
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 0%

---


# 用户：新用户会显示“未决批准”标记

>[!NOTE]
>
>已迁移到Adobe Admin Console的组织中可能存在此问题。

Workfront中的新用户可能显示在用户列表中，并带有“待审批”标记。 该徽章会持续存在超过几分钟，并在页面刷新时仍然存在。

批量上传用户(例如从电子表格或Workfront Kick-Start上传)时，这一问题会加剧。

预期行为是徽章在几分钟后消失，并在页面刷新时不存在。

## 解决方法

当添加到Workfront的用户未同步到Adobe Admin Console时，会发生这种情况。

我们建议采取以下解决方法：

### 解析单个用户

您可以解析“用户”列表中的单个用户。

1. 在“用户”列表中选择一个或多个用户。
1. 单击列表标题中的三个圆点菜单。
1. 选择&#x200B;**批准**。
1. 几分钟后，刷新页面。

### 解析添加了大量批次的用户

要解决批量添加的用户，可以直接将批量用户添加到Adobe Admin Console。

有关说明，请参阅[管理多个用户 | 在Adobe文档中批量CSV上传](https://helpx.adobe.com/cn/enterprise/using/bulk-upload-users.html)。


_首次报告于2025年5月8日。_
