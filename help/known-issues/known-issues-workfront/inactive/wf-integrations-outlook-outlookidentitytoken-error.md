---
title: 集成：使用Workfront for Outlook时出现outlookIdentityToken错误
description: 当用户使用Workfront for Outlook集成时，他们可能会看到错误。
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# 集成：使用Workfront for Outlook时出现outlookIdentityToken错误

当用户使用Workfront for Outlook集成时，他们可能会看到以下错误：

```
Unexpected error
Unable to get the outlookIdentityToken
```

**解决方法**


要解决此错误，您必须为组织启用Microsoft 365旧版令牌。 由于必须在Microsoft 365中完成此设置，因此Workfront无法为您的组织启用这些令牌。

有关启用Microsoft 365旧版令牌的说明，请参阅Microsoft文档中的[打开或关闭旧版Exchange Online令牌](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off)。

有关旧版令牌的详细信息，请参阅[我能否重新启用Exchange Online旧版令牌？Microsoft文档中的](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on)。


_首次报告于2025年3月3日。_
