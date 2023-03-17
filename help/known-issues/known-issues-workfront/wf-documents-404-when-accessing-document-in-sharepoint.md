---
title: “文档：404访问从SharePoint链接的文档时出错”
description: “当用户尝试访问通过SharePoint链接的文档时，他们会被带到页面，并出现404错误。”
hidefromtoc: true
source-git-commit: c95d478b78e26e4f0243e9b9ae69ecfbc016d696
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# 文档：404访问链接自的文档时出错 [!DNL SharePoint]

<!--This issue is on the WF and WFP TOCs-->

当用户尝试访问通过链接的文档时 [!DNL SharePoint]，则会将它们转到页面，并出现以下错误：

&quot;[!UICONTROL 错误404:未找到页面。 此页面不可用。 尝试检查URL或访问其他页面。]&quot;

这是已知的 [!DNL SharePoint] 当网站的链接中包含“@”符号时出现的问题。

**解决方法**

[!DNL SharePoint] 建议生成一个短url，并将其用于链接。

_首次报告于 2023 年 3 月 14 日。_

