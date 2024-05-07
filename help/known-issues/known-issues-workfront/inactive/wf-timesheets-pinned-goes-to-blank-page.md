---
title: “时间表：已固定的时间表转到空白页”
description: “当用户在Workfront中单击要转到其时间表的pin时，该pin将转到空白页。 有解决方法可用。"
hidefromtoc: true
feature: Timesheets
source-git-commit: 229d3accabec51a7c559279b680336ca096c0e70
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 4%

---


# 时间表：将时间表固定到空白页

当用户在Workfront中单击要转到其时间表的pin时，该pin将转到空白页。

这是因为时间表的URL已更改。 该 `/own` URL末尾的URL不再正确。 如果用户已固定包含的URL `/own`，则该销钉指向空白页。

**解决方法**

1. 取消固定时间表。
1. 移除 `/own` 从URL的末尾
1. 重新固定时间表。

_首次报告于2024年5月7日。_

