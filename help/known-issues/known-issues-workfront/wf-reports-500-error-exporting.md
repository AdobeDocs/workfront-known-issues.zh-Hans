---
title: '报告：导出报告时出现 500 错误'
description: 当用户尝试导出报告时，报告未导出，并且用户看到一个错误。 有解决方法可用。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 18%

---

# 报告：导出报告时出现 500 错误

>[!NOTE]
>
>此问题已于2024年4月5日修复。

当用户尝试导出报告时，报告未导出，并且用户看到以下错误消息：

500：无法调用“com.attask.biz.Parameter.getDisplayType()”，因为“parameter”为null /attask/api-internal/report/export

当报表引用项目级别的自定义货币字段时，会发生这种情况。

**解决方法**

删除引用自定义货币字段的列，然后再次导出报表。

_首次报告于2024年4月4日。_
