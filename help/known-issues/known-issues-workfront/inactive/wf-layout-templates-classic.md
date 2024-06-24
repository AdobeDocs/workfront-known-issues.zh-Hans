---
title: '布局模板：布局模板导致报告中出现不一致'
description: 经典 Workfront 体验中的布局模板在 Workfront 界面中不再可用，但仍可能会影响 Workfront 数据。这可能会导致报告或仪表板上受布局模板影响的字段（如“共享对象”）中出现不一致。
hidefromtoc: true
feature: System Setup and Administration
exl-id: 1542291f-4797-477e-83b8-0706ac6801ae
source-git-commit: 875945978c7bdb4a7128ade826b6fbc31da04ae9
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 100%

---

# 布局模板：布局模板导致报告中出现不一致

<!--Can delete after 9/24/2024-->

>[!NOTE]
>
>已解决此问题。

经典 [!DNL Workfront] 体验中的布局模板在 [!DNL Workfront] 界面中不再可用，但仍可能会影响 [!DNL Workfront] 数据。这可能会导致报告或仪表板上受布局模板影响的字段（如[!UICONTROL 共享对象]）中出现不一致。

**变通方法**

使用 API 调用删除经典布局模板。您必须登录到 Workfront。

>[!NOTE]
>
>无法删除全局和系统布局模板。

1. 使用以下 API 调用找到要删除的布局模板：
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. 记下要删除的布局模板的 ID。
1. 使用以下 API 调用找到您的会话 ID：
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >请勿与任何人分享您的会话 ID。

1. 将布局模板 ID 和会话 ID 插入到以下 API 调用中：
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. 将第 4 步中的 API 调用粘贴到浏览器的 URL 栏中，然后按 Enter。

   这样将删除该布局模板。
