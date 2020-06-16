---
title: "Learning Arbitration for Shared Autonomy"
date: 2019-06-22T17:05:36-08:00
categories:
  - Blog
tags:
  - sharedControl
---

*Shared control* combines human intelligence and the robot's autonomy to better control the robotic system. It combines "both of best worlds" where humans are good at perceiving and decision making in complex, dynamic environments and taking the advantage of computation and optimization of the robot agent.

The two policies are blended using an *arbitration function*, i.e. linear blending. Here, the arbitration parameter \alpha can depend on different factor like the confidence in the user intent prediction. 