---
title: 权限：对象权限未正确继承
description: 继承的权限未能正确应用到对象上。 这可能是由于权限继承关系过于复杂导致的。
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 100%
---
# 权限：对象权限未正确继承

>[!NOTE]
>
>产品团队目前正在评估此问题的解决方案，这可能需要产品增强功能。 产品增强功能在“产品公告”中而非“维护更新”中传送。

继承的权限未能正确应用到对象上。 这可能是由于权限继承关系过于复杂所致，具体可能受以下因素影响：

* 该对象与大量用户共享
* 一次权限继承变更影响了大量对象

**解决方法**

限制对象的规模或复杂度有助于避免此问题。 我们建议任何父对象下的子对象数量不超过 10,000 个。

_首次报告于 2025 年 3 月 21 日。_
