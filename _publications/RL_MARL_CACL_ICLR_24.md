---
title: "Learning Multi-Agent Communication with Contrastive Learning"
collection: publications
permalink: /publication/RL_MARL_CACL_ICLR_24
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-01-31
venue: '<i>The 11th International Conference on Learning Representations (ICLR)</i>'
paperurl: 'https://richielo.github.io/files/RL_MARL_CACL_ICLR_24.pdf'
citation: '<b>Lo, Yat Long</b>, Biswa Sengupta, Jakob Foerster, Michael Noukhovitch. <i>In Proceedings of The 11th International Conference on Learning Representations </i>. ICLR 2024.'
---
[[PDF]](https://richielo.github.io/files/RL_MARL_CACL_ICLR_24.pdf)

## Abstract
Communication is a powerful tool for coordination in multi-agent RL. But inducing an effective, common language is a difficult challenge, particularly in the decentralized setting. In this work, we introduce an alternative perspective where communicative messages sent between agents are considered as different incomplete views of the environment state. By examining the relationship between messages sent and received, we propose to learn to communicate using contrastive learning to maximize the mutual information between messages of a given trajectory. In communication-essential environments, our method outperforms previous work in both performance and learning speed. Using qualitative metrics and representation probing, we show that our method induces more symmetric communication and captures global state information from the environment. Overall, we show the power of contrastive learning and the importance of leveraging messages as encodings for effective communication.