---
layout: post
fromdate: 2013
todate: 2018
title: CITRIX 与SPICE瘦客户端适配（威盛电子）
#inline: true
---
== 为WM8950适配Citrix Client为ZX1000适配 Spice 客户端==
===项目简介：===

客户要在WonderMedia WM8950使用Citrix Linux Client. Citrix 可以把Video Streaming 重定向到Linux Client。Client则要把重定向的视频流解码，并显示在指定位置（可能全屏显示，也可能不全屏幕）。同时桌面传输格式为jpeg需要通过hardware进行jpeg解码，已提高桌面APP流畅。色彩空间转换则通过Neon加速。