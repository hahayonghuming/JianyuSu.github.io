---
title: "Deep Multi-Agent Reinforcement Learning for Multi-Level Preventive Maintenance in Manufacturing Systems"
collection: publications
permalink: /publications/MAPM
venue: "Expert Systems With Applications(Journal)"
date: 2021-11-07
citation: '<b>Jianyu Su</b>, Jing Huang, Stephen Adams, Qing Chang, Peter A. Beling. <i>Accepted by Journal Expert Systems With Applications</i>.'
---

## Abstract
Designing preventive maintenance (PM) policies that ensure smooth and efficient production for large-scale manufacturing systems is non-trivial. 
Recent model-free reinforcement learning (RL) methods shed lights on how to cope with the non-linearity and stochasticity in such complex systems. 
However, the action space explosion impedes RL-based PM policies to be generalized to real applications. In order to obtain cost efficient PM 
policies for a serial production line that has multiple levels of PM actions, a novel multi-agent modeling is adopted to support adaptive learning 
by modeling each machine as cooperative agent. The evaluation of system-level production loss is leveraged to construct the reward function. An 
adaptive learning framework based on value-decomposition multi-agent actor-critic algorithm is utilized to obtain PM policies. In simulation study, 
the proposed framework demonstrates its effectiveness by leading other baselines on a comprehensive set of metrics whereas the centralized RL-based 
methods struggles to converge to stable policies. Our analysis further demonstrates that our multi-agent reinforcement learning based method learns
effective PM policies without any knowledge about the environment and maintenance strategies.
