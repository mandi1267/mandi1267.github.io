---
title: POM-Localization
layout: post
banner: /images/pom_loc.png
category: project
excerpt: Can we learn and leverage the patterns in where movable objects occur...
---

Published/presented at IROS 2022. 

Links: [[paper](https://arxiv.org/abs/2110.00128)] [[video](https://youtu.be/P4VFh5kD_CE)] [[github](https://github.com/ut-amrl/pom_localization/tree/semanticPoints)]

Authors: Amanda Adkins, Taijing Chen, [Joydeep Biswas](https://www.joydeepb.com)

Can we learn and leverage the patterns in where movable objects occur to improve localization robustness?

![POM Localization](/images/pom_loc.png)  

Robots deployed in settings such as warehouses and parking lots must cope with frequent and substantial changes when localizing in their environments. While many previous localization and mapping algorithms have explored methods of identifying and focusing on long-term features to handle change in such environments, we propose a different approach – can a robot understand the *distribution* of movable objects and relate it to observations of such objects to reason about global localization? In this paper, we present probabilistic object maps (POMs), which represent the distributions of movable objects using pose-likelihood sample pairs derived from prior trajectories through the environment and use a Gaussian process classifier to generate the likelihood of an object at a query pose. We also introduce POM-Localization, which uses an observation model based on POMs to perform inference on a factor graph for globally consistent long-term localization. We present empirical results showing that POM-Localization is indeed effective at producing globally consistent localization estimates in challenging real-world environments, and that POM-Localization improves trajectory estimates even when the POM is formed from partially incorrect data.

Checkout the [arXiv entry](https://arxiv.org/abs/2110.00128) and our (shorter) [results](https://youtu.be/0HoudDB_9UM) and (longer) [explainer](https://youtu.be/P4VFh5kD_CE) videos.

