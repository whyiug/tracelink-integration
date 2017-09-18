# 手动操作 \( SNX & SOM Manually \)

## 简述

这一章讲解了在Tracelink平台的人工操作。

在没有类似RED4S/SDC这样好用的系统时，企业可以手动进行这样的操作。

## 名词解释

> reserved: 保留；生成或获取到序列码的初始状态；
>
> encoded: 印刷；从系统中导出提供给印刷出；
>
> commissioned: 赋码；在产线上喷印或者贴标；
>
> decommissioned: 解除赋码；decommissioned的序列码可以继续commission；
>
> aggregated: 关联；小中大建立关联关联；
>
> disaggregated: 解除关联；解除关联之后可以重新关联；
>
> deactivated: 失活；标记**未被使用过的**序列码不再使用；一般原因为企业向跳过某些序列号；
>
> destroyed: 销毁；只有commissioned状态的序列码可以被销毁；抽检留样，留取样张，废弃等都可以作为销毁事件；

## 序列码的流转周期

![](/assets/2.1import.png)

## 注意

> 只有reserved状态才可以操作deactivated event；
>
> 只有commissioned状态才可以操作destoryed event；
>
> destroyed event 包括damaged, recalled, sampled, expired等



