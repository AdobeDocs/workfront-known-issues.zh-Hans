---
title: “报告：导出报告时出现500错误”
description: “当用户尝试导出报告时，报告未导出，并且用户看到一个错误。 有变通方法可用。"
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 1f516bdbea40c2946dec1935b7ada63b28b3451c
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 12%

---


# 报告：导出报告时出现 500 错误

当用户尝试导出报告时，报告未导出，并且用户看到以下错误消息：

500：无法调用“com.attask.biz.Parameter.getDisplayType()”，因为“parameter”为null /attask/api-internal/report/export

当报表引用项目级别的自定义货币字段时，会发生这种情况。

**解决方法**

删除引用自定义货币字段的列，然后再次导出报表。

_首次报告于2024年4月4日。_
