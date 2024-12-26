---
title: 校样：不会生成网络捕获校样
description: 当用户尝试创建网络捕获校样时，无法成功生成校样。
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: ht
source-wordcount: '98'
ht-degree: 100%

---

# 校样：不会生成网络捕获校样

>[!NOTE]
>
>此问题已关闭，因为它已按预期运行。请参阅下面的解决方法。

当用户尝试创建网络捕获校样时，无法成功生成校样。

**解决方法**

此问题是由于某些 PDF 文件的校样生成时间过长而导致的。要将生成超时时间从默认的 30 秒增加，请在 Proof Admin 的帐户级别的处理设置中编辑以下属性：

`WebCaptureNavigationTimeout -> 120`

_首次报告于 2024 年 10 月 3 日。_
