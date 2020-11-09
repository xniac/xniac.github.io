---
layout: archive
title: "Research Highlights"
permalink: /researches/
author_profile: true
---

**Cooperative Policy Learning with Pre-trained Heterogeneous Observation Representations**<br>
<br><img src = "\images\EncGat_Architecture.jpg"
    alt = "EncGat Architecture"
    height = "300" a=""
    />
- Propose an encoder-decoder based graph attention module to accurately represent the complicated interactions between heterogeneous entities in the Multi-Agent System.
- Introduce the pre-training with a local actor-critic algorithm for cooperative policy learning, through which each agent gain intelligence through selfish policy learning. And the pre-trained agents will be further trained for cooperative policy learning.
- Reduced the bike shortage rate by over 98% in CitiBike scenarios, outperformed the results of widely applied operational research solutions (76%); decreased the repositioning workload by about 40% and thus improved the repositioning efficiency.

<br><img src = "\images\marologo.svg"
    alt = "Maro Logo"
    height = "100" a=""
    />
**Multi-Agent Resource Optimization (MARO) platform**<br>
[github](https://github.com/microsoft/maro)<br>
*Collaborator

- Applied Multi-Agent Reinforcement Learning (MARL) to solve real-world combinatorial optimization problems: sharing bike repositioning and vitural machine allocation.
- Realized the Citibike and DCSim scenarios by building environment simulators with real-world data traces (from Azure and CitiBike).
- Optimize the simulation speed by 2.6x throught parallelizing the simulation over 22 CPU cores.