---
title: “报告：导出报告时出现500错误”
description: “当用户尝试导出报告时，导出失败并出现500错误。”
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 8fcd13b3586664d7540e64fb855f7f84e6e7cdc7
workflow-type: tm+mt
source-wordcount: '59'
ht-degree: 0%

---


# 报告：导出报告时出现500错误

当用户尝试导出报告时，导出失败并出现以下错误：

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

该问题已在使用 `valueexpression` 以引用 `lastNote` 注释文本。

_首次报告于2023年8月Novmeber。_
