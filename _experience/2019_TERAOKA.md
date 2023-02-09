---
layout: post
fromdate: 2019.06
todate: 2019.12
title: 日本TERAOKA POS 机（威盛电子）
#inline: true
---
## 负责威盛ODM客户TERAOKA对于X86平台 VX900的定制需求 

### 项目简介：
项目简介：
客户希望尽量小的改动客户应用程序，实现屏幕图像局部旋转。通过软件方式（CPU拷贝）旋转效果较差，希望能定制显示驱动。
客户订单量较大，因此提供定制。
给客户定制ioctl rotate参数，在pan display参数之前调用。根据rotate把相关buffer绑定实施旋转的硬件，在pan display显示时把旋转后的效果直接帖上屏幕(内存中实际数据并未做转置)。
此项目赢得了数亿订单，直到2022年该客户依然有稳定的订单。
