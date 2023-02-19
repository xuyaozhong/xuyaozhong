---
layout: post
fromdate: 2020.06
todate: now 
title: VIA HEADWAY DRIVERLESS CAR AND SIMULATED DRIVING（VIA）
#inline: true
---
##  VIA HEADWAY DRIVERLESS CAR AND SIMULATED DRIVING（VIA）

Responsible for the overall architecture design, responsible for the software development of Arm system and X86 industrial computer system.   

### Description：
Headway based on Autoware.AI 1.4/1.3, using lider/GNSS/Camera/mm wave radar to implement  self-driving。

Using WebRTC to transfer M810(Snapdragon 820) SVS H264 video，to implement remote  driving。
X86 PC run Autoware.AI, equipped with 16-line radar, and calls Open Planner to realize  
M810 collects sensor data through 5 can2.0 ports, sensors including vehicle chassis/ BMS/2 mm wave radar/ultrasonic radar.  Sensor service (running on M810) transmits messages to the cloud in real time. 
Using thread pool to improve throughput, Zmq pub/sub model to implement IPC. 
JSON as IPC/network data format. Using Open–closed principle in protocol definition.

