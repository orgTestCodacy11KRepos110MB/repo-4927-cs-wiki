---
title: Untitled
date: 2021-01-18 10:58:30
permalink: /pages/c1ef60/
---
## 无人驾驶决策技术

无人驾驶技术的决策模块目的是为了保证无人驾驶车辆的行车安全，并遵守当前场景的交通规则，输出合理的控制动作给下一层的控制模块。



目前，**无人驾驶车辆的决策模块主要还是根据上层模块的输出来制定车辆控制策略**，然而这种决策过程弊端太大，过分依赖上层模块的输出导致系统鲁棒性不强，同时，由于引入了人类先验知识，导致每个决策模块可能只适应于特定的场景，很难适应复杂多变的场景。

因此，现今的无人驾驶车辆的自动化程度有限，很大一部分原因归根于欠缺自适应的决策算法