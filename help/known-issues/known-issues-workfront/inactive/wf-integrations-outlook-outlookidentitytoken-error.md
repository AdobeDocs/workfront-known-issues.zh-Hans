---
title: 集成：使用 Workfront for Outlook 时出现 outlookIdentityToken 错误
description: 当用户使用 Workfront for Outlook 集成时，他们可能会看到错误。
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 87%

---

# 集成：使用 Workfront for Outlook 时出现 outlookIdentityToken 错误

>[!NOTE]
>
>Workfront for Outlook集成不再可用。 本文将在不久的将来删除。

当用户使用 Workfront for Outlook 集成时，他们可能会看到以下错误：

```
Unexpected error
Unable to get the outlookIdentityToken
```

**解决方法**


要解决此错误，您必须为您的组织启用 Microsoft 365 旧版令牌。因为这必须在 Microsoft 365 中完成，所以 Workfront 无法为您的组织启用这些令牌。

有关启用 Microsoft 365 旧版令牌的说明，请参阅 Microsoft 文档中的[打开或关闭旧版 Exchange Online 令牌](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off)。

有关旧版令牌的更多信息，请参阅[我可以重新打开 Exchange Online 旧版令牌吗？Microsoft 文档中的 &#x200B;](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on)。


_首次报告于 2025 年 3 月 3 日。_
