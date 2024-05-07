---
title: “集成：通过集成发送到 AEM 时文件名为空”
description: ”当通过 Workfront 集成将大文件（超过 100 MB）发送到 Adobe Experience Manager 时，AEM 中的文件名为空。“
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
source-git-commit: 3ca57c76dc50a348cf6d85d4d3e7366834a5e791
workflow-type: tm+mt
source-wordcount: '104'
ht-degree: 50%

---

# 集成：文件名在发送到文档集成时为“null”

当通过Workfront集成向文档提供程序发送大文件（超过100 MB）时，文档提供程序中的文件名是“null”。

ZIP 和 TIF 文件均已报告此问题。

**解决方法**

执行下列操作之一：

* 将文档名称映射到文档提供商中的标题。
* 直接在文档提供程序中输入文件名。

_首次报告于 2024 年 4 月 23 日。_

