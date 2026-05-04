---
title: 用户：新用户显示“待审批”徽章
description: Workfront 中的新用户可能会在用户列表中显示“待审批”徽章。 该徽章会持续显示超过几分钟，即使刷新页面后仍然存在。
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 100%

---

# 用户：新用户显示“待审批”徽章

>[!NOTE]
>
>已迁移到 Adobe Admin Console 的组织中可能会出现此问题。

Workfront 中的新用户可能会在用户列表中显示“待审批”徽章。 该徽章会持续显示超过几分钟，即使刷新页面后仍然存在。

当通过电子表格或 Workfront 快速启动批量导入用户时，该问题会更加明显。

按预期行为，徽章应在几分钟后消失，并且刷新页面后不再显示。

## 解决方法

当添加到 Workfront 的用户未同步到 Adobe Admin Console 时，会出现此问题。

我们建议采用以下解决方法：

### 解决单个用户

您可以在“用户”列表中解决单个用户。

1. 在“用户”列表中选择一个或多个用户。
1. 点击列表标题中的三点菜单。
1. 选择&#x200B;**批准**。
1. 几分钟后刷新页面。

### 解决批量新增的用户

要解决批量新增用户的问题，您可以直接将这批用户添加到 Adobe Admin Console 中。

有关操作说明，请参阅 Adobe 文档中的[管理多个用户 | 批量上传 CSV](https://helpx.adobe.com/cn/enterprise/using/bulk-upload-users.html)。


_首次报告时间：2025 年 5 月 8 日。_
