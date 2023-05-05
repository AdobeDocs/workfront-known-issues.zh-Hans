---
title: '文档：访问从 SharePoint 链接的文档时出现 404 错误'
description: 当用户尝试访问通过 SharePoint 链接的文档时，他们被带到一个页面，其中显示 404 错误。
hidefromtoc: true
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
source-git-commit: 17906db6aadc416c8be01e60d1b796143c97c061
workflow-type: ht
source-wordcount: '104'
ht-degree: 100%

---

# 文档：访问从 [!DNL SharePoint] 链接的文档时出现 404 错误

<!--This issue is on the WF and WFP TOCs. By request.-->

“当用户尝试访问通过 [!DNL SharePoint] 链接的文档时，他们会被带到一个出现以下错误的页面：

”[!UICONTROL 错误 404：找不到页面。此页面不可用。请尝试检查 URL 或访问其他页面。]&quot;

这是一个已知的 [!DNL SharePoint] 问题，当站点的链接中包含“@”符号时会发生该问题。

**解决方法**

[!DNL SharePoint] 建议生成一个短 url，并将其用于该链接。

_首次报告于 2023 年 3 月 14 日。_
