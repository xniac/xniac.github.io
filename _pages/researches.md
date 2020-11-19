---
layout: archive
title: ""
permalink: /researches/
author_profile: true
---

Semi-supervised Few Shot Action Recognition
======
<span class="links">
  <a href="https://arxiv.org/abs/2011.08410">[Paper]</a>
  <a href="https://xniac.github.io/fsaa" target="_blank">[Website]</a>
  <a href="https://github.com/xniac/Few-shot-action-recognition">[GitHub]</a>
  </span>
  <br>
<br><img src = "\images\FS_Architecture.png"
    alt = "FS Architecture"
    height = "200" a=""
    />
- Adopted sliding windows for video segmentation and connectionist temporal classification (CTC) loss to train the video embedding with relatively loose alignment, providing accurate video embedding and more robust action recognition; developed a multi-head relational network to compare the video similarity, laying emphasis on both the entire action similarity and local similarity of action clips.
-	Involved the multi-head attention mechanism to extract the feature of an unseen class based on the given query videos, and recursively refined the feature of the query videos. This refinement extracts more representative features and allows more effective classification.
- Experiment result outperformed the state-of-the-art action classification (without few-shot learning) on a set of published datasets over a margin of about 5%.

Multi-Agent Sharing Bike Repositioning
======
<br><img src = "\images\EncGat_Architecture.jpg"
    alt = "EncGat Architecture"
    height = "300" a=""
    />
- Propose an encoder-decoder based graph attention module to accurately represent the complicated interactions between heterogeneous entities in the Multi-Agent System.
- Introduce the pre-training with a local actor-critic algorithm for cooperative policy learning, through which each agent gain intelligence through selfish policy learning. And the pre-trained agents will be further trained for cooperative policy learning.
- Reduced the bike shortage rate by over 98% in CitiBike scenarios, outperformed the results of widely applied operational research solutions (76%); decreased the repositioning workload by about 40% and thus improved the repositioning efficiency.

<br><img src = "\images\marologo.jpg"
    alt = "Maro Logo"
    width = "300" a=""
    /><br>

Multi-Agent Resource Optimization (MARO) platform
======
[\[github\]](https://github.com/microsoft/maro)<br>
*Collaborator
<br><img src = "\images\maro_overview.svg"
    alt = "MARO Overview"
    height = "300" a=""
    />

- Applied Multi-Agent Reinforcement Learning (MARL) to solve real-world combinatorial optimization problems: sharing bike repositioning and vitural machine allocation.
- Realized the Citibike and DCSim scenarios by building environment simulators with real-world data traces (from Azure and CitiBike).
- Optimize the simulation speed by 2.6x throught parallelizing the simulation over 22 CPU cores.