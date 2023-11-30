---
title: '报告：导出报告时出现500错误'
description: 当用户尝试导出报告时，导出失败并出现500错误。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '65'
ht-degree: 9%

---

# 报告：导出报告时出现500错误

>[!NOTE]
>
>此问题已于 2023 年 11 月 30 日修复。

当用户尝试导出报告时，导出失败并出现以下错误：

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

该问题已在使用 `valueexpression` 以引用 `lastNote` 注释文本。

_首次报告于2023年8月Novmeber。_
