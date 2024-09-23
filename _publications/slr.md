---
title: "SLR: Learning Quadruped Locomotion without Privileged Information"
collection: publications
category: conferences
permalink: /publication/slr
excerpt: 'This paper is about the locomotion of quadruped robots'
date: 2024-09-05
venue: 'Conference on Robot Learning'
paperurl: 'https://openreview.net/pdf?id=RMkdcKK7jq'
---

The recent mainstream reinforcement learning control for quadruped robots often relies on privileged information, demanding meticulous selection and precise estimation, thereby imposing constraints on the development process. This work proposes a Self-learning Latent Representation (SLR) method, which achieves high-performance control policy learning without the need for privileged information. To enhance the credibility of the proposed method's evaluation, SLR was directly compared with state-of-the-art algorithms using their open-source code repositories and original configuration parameters. Remarkably, SLR surpasses the performance of previous methods using only limited proprioceptive data, demonstrating significant potential for future applications. Ultimately, the trained policy and encoder empower the quadruped robot to traverse various challenging terrains

(https://tenthousandrain.github.io/images/net2.png)
Illustration of SLR training framework. All dashed lines represent the network updating process. The solid pink line indicates the encoder updates through backpropagation from the Critic network, the transition model, and random sampling. The remaining solid lines represent the net-work’s forward inference process.


[More information here](https://openreview.net/forum?id=RMkdcKK7jq&noteId=RMkdcKK7jq)
