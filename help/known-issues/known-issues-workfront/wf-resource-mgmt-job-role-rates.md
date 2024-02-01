---
title: “资源管理：由于工作角色问题，财务计算不正确”
description: “小时数和财务计算可能不正确，即使小时数记录在具有成本率的工作角色中，显示成本为0。”
hidefromtoc: true
feature: Resource Management
source-git-commit: e9a7ff289e7c9fcc9c9ff13b7c4b5b554e303c11
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 3%

---


# 资源管理：由于工作角色问题，财务计算不正确

小时数和财务计算可能不正确，即使小时数记录在具有成本率的工作角色中，显示成本为0。

这是因为工作角色会自动创建没有开始或结束日期的重复费率。 由于它们没有开始日期或结束日期，因此运行财务计算时，它们将被视为0值。

**变通方法**

1. 确保保存您过去正确的数据。
1. 删除没有开始或结束日期的重复费率。
1. 重新计算财务。

_首次报告于 2023 年 1 月 18 日。_