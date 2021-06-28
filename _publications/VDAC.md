---
title: "Value-Decomposition Multi-Agent Actor-Critics"
collection: publications
permalink: /publications/VDAC
venue: "The 35th AAAI Conference on Artificial Intelligence (AAAI 2021)"
date: 2021-02-02
citation: '<b>Jianyu Su</b>, Stephen Adams, and Peter A. Beling. 2021. <i>Proceedings of the AAAI Conference on Artificial Intelligence 35(13) 11352-60.
</i>'
---

[Download paper here](https://arxiv.org/abs/2007.12306)

## Abstract
The exploitation of extra state information has been an active research area in multi-agent reinforcement learning (MARL). QMIX represents the joint action-value using a non-negative function approximator and achieves the best performance, by far, on multi-agent benchmarks, StarCraft II micromanagement tasks. However, our experiments show that, in some cases, QMIX is incompatible with A2C, a training paradigm that promotes algorithm training efficiency. To obtain a reasonable trade-off between training efficiency and algorithm performance, we extend value-decomposition to actor-critics that are compatible with A2C and propose a novel actor-critic framework, value-decomposition actor-critics (VDACs). We evaluate VDACs on the testbed of StarCraft II micromanagement tasks and demonstrate that the proposed framework improves median performance over other actor-critic methods. Furthermore, we use a set of ablation experiments to identify the key factors that contribute to the performance of VDACs.
