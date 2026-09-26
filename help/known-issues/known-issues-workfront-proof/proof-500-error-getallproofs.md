---
title: Workfront Proof：通过API或Workfront Fusion访问Workfront Proof时出现500错误
description: 当用户访问验证API getAllProofs操作时，Workfront Proof服务器返回消息：500内部服务器错误
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 69%
---
# [!DNL Workfront Proof]：通过 API 或 [!DNL Workfront Fusion] 访问 [!DNL Workfront Proof] 时出现 500 错误

>[!NOTE]
>
>产品团队目前正在评估此问题的解决方案，这可能需要产品增强功能。 产品增强功能在“产品公告”中而非“维护更新”中传送。

<!--This article is on Proof and Fusion TOCs-->

当用户访问 [!DNL Workfront Proof] API [!UICONTROL `getAllProofs`] 操作时，服务器返回以下消息：

[!UICONTROL 500 内部服务器错误]

由于 [!DNL Workfront Fusion] 将 [!DNL Workfront Proof] API 用于 [!DNL Workfront Proof] 模块，因此，该错误可能会返回到一个模块，从而停止场景。

_首次报告于 2023 年 4 月 28 日。_
