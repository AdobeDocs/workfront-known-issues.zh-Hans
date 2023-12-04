---
title: '报告：导出报告时出现 500 错误'
description: 当用户尝试导出报告时，导出失败并出现 500 错误。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '70'
ht-degree: 91%

---

# 报告：导出报告时出现 500 错误

>[!NOTE]
>
>此问题已于2023年11月30日修复。

当用户尝试导出报告时，导出失败并出现以下错误：

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

在使用 `valueexpression` 引用 `lastNote` 注释文本的报告中已经报告了这一点。

_首次报告于 2023 年 11 月 8 日。_
