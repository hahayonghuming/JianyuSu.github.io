---
title: "Towards Personalized User-Ad Retrieval for Display Advertising at JD.com"
collection: publications
permalink: /publications/EmbedDMP
venue: "arXiv"
date: 2022-1-28
citation: '<b>Jianyu Su</b>, Sen Li, Liang Feng, Linrong Jin, Zhenfang Guo, Jinghe Hu, Hao Wang.'
---

<!-- [Download paper here](https://arxiv.org/abs/2004.00470) -->

## Abstract
The display advertising system at JD.com adopts a widely used multi-stage cascade architecture that comprises matching, ranking, etc. The matching system is responsible for targeting relevant ads from tens of millions ads while the rest of the system concerns about business values (eg, CTR, eCPM) of those ads. The separation in objectives between the matching system and its subsequent systems often causes performance losses of the whole display advertising system. Regardless of the targeting method that is applied in the matching, the matching system is constantly experiencing the issue of truncating relevant ads as it is restrained from applying targeting methods on every ad due to the latency limitation. That is to say, not all ads get to participate in the online matching. Truncation of relevant ads not only hurts advertisers' user experience, but also brings revenue loss for the platform. As such, We rethink the matching process and design a hybrid matching engine that balance the delicate trade-off between inclusion of user-related ads and system limitations. The basic idea is to prioritize user-related ads in the matching queue, thereby preventing them from being truncated. Specifically, a learning-based relevance module is adopted to identify user-related ads during the matching, followed by boolean expression match to conduct targeting. The advantage of such hybrid matching system is two-fold: introduction of the learning-based relevance module mitigates the issue of objective mismatch as its objective can be adjusted according to subsequent systems such as the ranking; prioritization of user-related ads attenuates the truncation of relevant ads in face of latency limitation. To cope with the abysmal latency resulted from the introduction of learning-based relevance module, we exploit approximate nearest neighbor techniques to achieve efficient identification of user-related ads in the matching step. The newly designed matching engine is approved to be effective in our evaluation and has been deployed in the display advertising system at JD.com. This paper is devoted to elaborate on various aspects of the design and launching of the proposed matching system.
