---
title: '报告：导出报告时出现 500 错误'
description: 当用户尝试导出报告时，报告无法导出，并且用户看到一条错误信息。有解决方法可用。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 100%

---

# 报告：导出报告时出现 500 错误

>[!NOTE]
>
>此问题已于 2024 年 4 月 5 日修复。

当用户尝试导出报告时，报告无法导出，并且用户看到以下错误：

500：无法调用“com.attask.biz.Parameter.getDisplayType()”，因为“参数”为空/attask/api-internal/report/export

当报告引用项目级自定义货币字段时，就会发生这种情况。

**解决方法**

移除引用自定义货币字段的列并再次导出报告。

_首次报告于 2024 年 4 月 4 日。_
