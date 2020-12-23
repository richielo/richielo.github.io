---
title: "Knowing When To Look Back: Bidirectional Rollouts in Dyna-style Planning"
collection: publications
permalink: /publication/RL_BDRL_ICAPS_WS_20
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2020-10-22
venue: '<i>ICAPS-20 Workshop on Bridging the Gap Between AI Planning and Reinforcement Learning </i>'
paperurl: 'https://richielo.github.io/files/RL_BDRL_ICAPS_WS_20.pdf'
citation: '<b>Lo, Yat Long</b>, Jia Pan and Albert Y.S. Lam. <i>ICAPS
Workshop on Bridging the Gap Between AI Planning and Reinforcement Learning</i>. 2020.'
---
[[PDF]](https://richielo.github.io/files/RL_BDRL_ICAPS_WS_20.pdf)

## Abstract
In model-based reinforcement learning (MBRL), a model of the world is used to generate transitional data for an agent to learn from, in order to reduce sample complexity. Dyna is one of the most widely adopted MBRL frameworks that perform planning, acting, and learning in an online manner. Most of the previous works on Dyna perform one-step rollouts from sampled states to generate data based on the agent’s history. Recently, it has been shown that planning shape and directionality (forward or backward planning) of the rollouts can impose a significant impact on the performance given a fixed planning budget.

In this work, we conduct a systematic study on how these two factors affect the performance of model-based agents. We hypothesize that forward planning and backward planning serve complementary purposes, i.e. exploration and value propagation, in which careful state-dependent allocation of planning budget can improve learning efficiency. We further provide an online method to automate the decision between forward planning and backward planning using error-based epistemic uncertainty. We examine our proposed method in the tabular and linear function approximation settings for both perfect and learned models on GridWorld and Cartpole environments and propose the use of an ensemble of world models to counter compounding errors of long rollouts in the learned models. Our results show that both planning shape and directionality have a profound impact on Dyna methods’ efficacy and bidirectional rollouts can improve learning efficiency using the same number of planning steps.
