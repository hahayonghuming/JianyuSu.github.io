---
title: "Is my sensor sleeping, hibernating, or broken? A data-driven monitoring system for indoor energy harvesting sensors"
collection: publications
permalink: /publications/SensorValid
venue: "The 7th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation (BuildSys 2020)"
date: 2020-11-19
citation: Alan Wang,<b> Jianyu Su</b>, Arsalan Heydarian, Bradford Campbell, and Peter A. Beling. <i>The 7th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation</i>. <b>BuildSys 2020</b>.'
---

[Download paper here](https://dl.acm.org/doi/abs/10.1145/3408308.3427625)

## Abstract
As the number of Internet of Things (IoT) devices continues to increase, energy-harvesting (EH) devices eliminate the need to replace batteries or find outlets for sensors in indoor environments. This comes at a cost, however, as these energy-harvesting devices introduce new failure modes not present in traditional IoT devices: extended periods of no harvestable energy cause them to go dormant, their often simple wireless protocols are unreliable, and their limited energy reserves prohibit many diagnostic features. While energy-harvesting sensors promise easy-to-setup and maintenance-free deployments, their limitations hinder robust, long-term data collection.

To continuously monitor and maintain a network of energy-harvesting devices in buildings, we propose the EH-HouseKeeper. EH-HouseKeeper is a data-driven system that monitors EH device compliance and predicts healthy signal zones in a building based on the existing gateway location(s) and building profile for easier device maintenance. EH-HouseKeeper does this by first filtering excess event-triggered data points and applying representation learning on building features that describe the path between the gateways and the device.

We assessed EH-HouseKeeper by deploying 125 energy-harvesting sensors of varying types in a 17,000 square foot research infrastructure, randomly masking a quarter of the sensors as the test set for validation. The results of our 6-month data-collection period demonstrate an average greater than 80% accuracy in predicting the health status of the subset. Our results validate techniques for assessing sensor health status across device types, for inferring gateway status, and approaches to assist in identifying between gateway, transmission, and sensor faults.
