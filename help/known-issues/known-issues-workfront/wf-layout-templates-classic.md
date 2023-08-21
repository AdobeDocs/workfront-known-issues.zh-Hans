---
title: “布局模板：布局模板导致报表不一致”
description: “经典Workfront Experience中的布局模板在Workfront界面中不再可用，但仍可能会影响Workfront数据。 这可能会导致报表或功能板中受布局模板（例如共享对象）影响的字段不一致。”
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 045e2bd200aa2fffaf2e763a73eb8729517be197
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---


# 布局模板：布局模板导致报表不一致

经典Workfront Experience中的布局模板在Workfront界面中不再可用，但仍可能会影响Workfront数据。 这可能会导致报表或功能板中受布局模板（例如“共享对象”）影响的字段不一致。

**解决方法**

使用API调用删除经典布局模板。 您必须登录到Workfront。

>[!NOTE]
>
>无法删除全局和系统布局模板。

1. 使用以下API调用找到要删除的布局模板：
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. 记下要删除的布局模板的ID。
1. 使用以下API调用找到您的会话ID：
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >切勿与任何人共享您的会话ID。

1. 将布局模板ID和会话ID插入以下API调用：
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. 将步骤4中的API调用粘贴到浏览器的URL栏中，然后按Enter。

   这将删除布局模板。

