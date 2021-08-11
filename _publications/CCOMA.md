---
title: "Counterfactual multi-agent reinforcement learning with graph convolution communication"
collection: publications
permalink: /publications/CCOMA
venue: "arXiv"
date: 2020-4-1
citation: '<b>Jianyu Su</b>, Stephen Adams, Peter A. Beling. <i>arXiv:2004.00470s</i>.'
---

[Download paper here](https://arxiv.org/abs/2004.00470)

## Abstract
We consider a fully cooperative multi-agent system where agents cooperate to maximize a system's utility in a partial-observable environment. We propose that multi-agent systems must have the ability to (1) communicate and understand the inter-plays between agents and (2) correctly distribute rewards based on an individual agent's contribution. In contrast, most work in this setting considers only one of the above abilities. In this study, we develop an architecture that allows for communication among agents and tailors the system's reward for each individual agent. Our architecture represents agent communication through graph convolution and applies an existing credit assignment structure, counterfactual multi-agent policy gradient (COMA), to assist agents to learn communication by back-propagation. The flexibility of the graph structure enables our method to be applicable to a variety of multi-agent systems, e.g. dynamic systems that consist of varying numbers of agents and static systems with a fixed number of agents. We evaluate our method on a range of tasks, demonstrating the advantage of marrying communication with credit assignment. In the experiments, our proposed method yields better performance than the state-of-art methods, including COMA. Moreover, we show that the communication strategies offers us insights and interpretability of the system's cooperative policies.
