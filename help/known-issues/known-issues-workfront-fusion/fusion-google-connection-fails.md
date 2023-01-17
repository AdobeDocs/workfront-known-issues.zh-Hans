---
title: 'Workfront Fusion：无法创建与 Google 的连接'
description: 当用户尝试在任何 Google 连接器（例如 Google Sheets 或 Google Drive）中创建连接时，不会创建连接并且用户会看到各种错误消息。
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: ht
source-wordcount: '109'
ht-degree: 100%

---

# [!DNL Workfront Fusion]：无法创建与 [!DNL Google] 的连接

>[!NOTE]
>
>此问题已于 2023 年 1 月 9 日修复。

当用户尝试在任何 [!DNL Google] 连接器（例如 [!DNL Google Sheets] 或 [!DNL Google Drive]）中创建连接时，他们会看到一个显示以下错误消息的窗口：

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

当用户关闭此窗口时，连接失败并在 [!DNL Fusion] 中出现以下错误：

“[!UICONTROL 错误：由于上一请求失败，导致此请求失败。 未指定访问令牌。]”

_首次报告于 2022 年 11 月 21 日。_
