---
title: 文档：访问从SharePoint链接的文档时出现404错误
description: 当用户尝试访问通过 SharePoint 链接的文档时，他们被带到一个页面，其中显示 404 错误。
feature: Digital Content and Documents, Workfront Integrations and Apps
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a1f87682-0525-5459-aa06-3560bb4c3b2a
    internal-label: Workfront Integrations and Apps
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 91%
---
# 文档：访问从 [!DNL SharePoint] 链接的文档时出现 404 错误

<!--Requested article. This issue is on the WF and WFP TOCs.-->

“当用户尝试访问通过 [!DNL SharePoint] 链接的文档时，他们会被带到一个出现以下错误的页面：

”[!UICONTROL 错误 404：找不到页面。 此页面不可用。 请尝试检查 URL 或访问其他页面。]&quot;

这是一个已知的 [!DNL SharePoint] 问题，当站点的链接中包含“@”符号时会发生该问题。

**解决方法**

[!DNL SharePoint] 建议生成一个短 URL，并将其用于该链接。

_首次报告于 2023 年 3 月 14 日。_
