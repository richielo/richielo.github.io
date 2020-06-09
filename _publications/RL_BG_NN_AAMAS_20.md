---
title: "Improving Performance in Reinforcement Learning by Breaking Generalization in Neural Networks"
collection: publications
permalink: /publication/RL_BG_NN_AAMAS_20
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2020-03-16
venue: '<i>The 19th International Conference on Autonomous Agents and Multi-Agent Systems (AAMAS 2020) </i>, 2020'
paperurl: 'https://richielo.github.io/files/RL_BG_NN_AAMAS_20.pdf'
citation: 'Ghiassian, Sina, Banafsheh Rafiee, <b>Yat Long Lo</b>, Adam White. <i>In Proceedings of the 19th International Conference on Autonomous Agents and Multi-Agent Systems</i>. <b>AAMAS 2020</b>.'
---
[[PDF]](https://richielo.github.io/files/RL_BG_NN_AAMAS_20.pdf)

## Abstract
Reinforcement learning systems require good representations to work well. For decades practical success in reinforcement learning was limited to small domains. Deep reinforcement learning systems, on the other hand, are scalable, not dependent on domain specific prior knowledge and have been successfully used to play Atari, in 3D navigation from pixels, and to control high degree of freedom robots. Unfortunately, the performance of deep reinforcement learning systems is sensitive to hyper-parameter settings and architecture choices. Even well tuned systems exhibit significant instability both within a trial and across experiment replications. In practice, significant expertise and trial and error are usually required to achieve good performance. One potential source of the problem is known as catastrophic interference: when later training decreases performance by overriding previous learning. Interestingly, the powerful generalization that makes Neural Networks (NN) so effective in batch supervised learning might explain the challenges when applying them in reinforcement learning tasks.

In this paper, we explore how online NN training and interference interact in reinforcement learning. We find that simply re-mapping the input observations to a high-dimensional space improves learning speed and parameter sensitivity. We also show this preprocessing reduces interference in prediction tasks. More practically, we provide a simple approach to NN training that is easy to implement, and requires little additional computation. We demonstrate that our approach improves performance in both prediction and control with an extensive batch of experiments in classic control domains.
