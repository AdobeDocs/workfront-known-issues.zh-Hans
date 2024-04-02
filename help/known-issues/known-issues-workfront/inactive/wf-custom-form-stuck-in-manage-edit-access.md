---
title: “自定义表单：跨对象自定义表单需要管理或者编辑权限来编辑字段”
description: 当用户使用仅允许“管理”或“编辑”权限的交叉对象创建表单，然后移除该对象类型时，自定义表单继续需要“管理”或“编辑”权限才能编辑字段。 没有可见指示表明字段需要“管理”或“编辑”权限，也无法重置表单。
hidefromtoc: true
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
source-git-commit: 688d728782638489aacc76a1a12c38ab12215f8e
workflow-type: ht
source-wordcount: '184'
ht-degree: 100%

---

# 自定义表单：跨对象自定义表单需要[!UICONTROL 管理]或者[!UICONTROL 编辑]权限来编辑字段

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>此问题已关闭

当用户使用仅允许“[!UICONTROL 管理]”或“[!UICONTROL 编辑]”权限的交叉对象创建表单，然后移除该对象类型时，自定义表单继续需要“[!UICONTROL 管理]”或“[!UICONTROL 编辑]”权限才能编辑字段。 没有可见指示表明字段需要“管理”或“编辑”权限，也无法重置表单。

**解决方法**

1. 如果使用填充，则使用默认值向表单添加分区界限。
2. 将分区界限移到表单的顶部。
3. 保存表单。
4. 移除刚刚添加的分区界限并重新保存表单。

_首次报告于 2022 年 11 月 9 日。_
