---
layout: post
fromdate: 2019.06
todate: 2019.12
title: TERAOKA POS （VIA）
#inline: true
---
## TERAOKA’s customization requirements for X86 platform VX900

### Description：
The effect of rotation by software (CPU copy) is poor, and it is hoped that the VX900 fb driver can be customized.
Implement private ioctl. Using mmap to map customer’s buffer in fb, then ioctl set width/height/stride/rotation. hardware can show the rotated data on screen. (The data in fb is not rotate)
