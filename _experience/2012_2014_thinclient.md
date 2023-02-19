---
layout: post
fromdate: 2013
todate: 2018
title: Citrix and SPICE thin client development（VIA）
#inline: true
---
## Adapt Citrix Client for WM8950, Adapt Spice client for ZX1000

### Description：

Customers want to use Citrix Linux Client on Wonder Media WM8950. Citrix can redirect Video Streaming to Linux Client. The client needs to decode the video stream and display it at the specified position (maybe full screen or not full screen).  At the same time, the desktop transmission format is jpeg, which needs to be decoded by hardware.
Color space conversion was accelerated by Neon.
