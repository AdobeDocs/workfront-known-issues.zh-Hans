---
title: “Workfront融合：无法创建与Google的连接”
description: “当用户尝试在任何Google连接器(如Google表或Google驱动器)中创建连接时，将不会创建该连接，并且用户会看到各种错误消息。”
hidefromtoc: true
source-git-commit: 7d50ddbd99edf3421ce92564590a2d8db76ae939
workflow-type: tm+mt
source-wordcount: '103'
ht-degree: 3%

---


# [!DNL Workfront Fusion]:无法创建与的连接 [!DNL Google]

当用户尝试在 [!DNL Google] 连接器(例如 [!DNL Google Sheets] 或 [!DNL Google Drive])，则他们会看到一个打开的窗口，并出现以下错误：

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

当用户关闭此窗口时，连接失败，内部出现以下错误 [!DNL Fusion]:

&quot;[!UICONTROL 错误：请求因先前请求失败而失败。 未指定访问令牌。]&quot;

_首次报告于 2022 年 11 月 21 日。_

