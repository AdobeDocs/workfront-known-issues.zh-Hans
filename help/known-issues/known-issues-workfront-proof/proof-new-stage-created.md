---
title: 校样：由于截止日期与现有阶段的截止日期不匹配，因此创建了新阶段
description: 创建新校样时，可以以 15 分钟为增量设置截止时间（10:00、10:15、10:30、20:45 等）。 但是，在创建校样后将用户添加到校样时，截止时间只能以 30 分钟为增量设置（10:00、10:30、11:00 等）。
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
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
source-wordcount: '243'
ht-degree: 64%
---
# 校样：由于截止日期与现有阶段的截止日期不匹配，因此创建了新阶段

<!--Requested article-->

创建新校样时，可以以 15 分钟为增量设置截止时间（10:00、10:15、10:30、20:45 等）。 但是，在创建校样后将用户添加到校样时，截止时间只能以 30 分钟为增量设置（10:00、10:30、11:00 等）。 因此，无法将新用户添加到截止日期以：15或：45结尾的阶段，因为无法匹配截止日期。 相反，新用户会添加到新阶段，截止时间设置为 30 分钟增量。

**解决方法**：

* 如果选择新验证的截止时间，请将截止时间设置为以：00或：30结束的时间（10:00、10:30、11:00等）。
* 如果在创建验证时自动设置了截止时间，请将验证的截止时间手动设置为以：00或：30结束的时间（10:00、10:30、11:00等）。
