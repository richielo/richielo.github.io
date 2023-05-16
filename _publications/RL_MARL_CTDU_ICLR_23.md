---
title: "Cheap Talk Discovery and Utilization in Multi-Agent Reinforcement Learning"
collection: publications
permalink: /publication/RL_MARL_CTDU_ICLR_23
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-01-31
venue: '<i>The 11th International Conference on Learning Representations (ICLR)</i>'
paperurl: 'https://richielo.github.io/files/RL_MARL_CTDU_ICLR_23.pdf'
citation: '<b>Lo, Yat Long</b> and Sina Ghiassian. <i>In Proceedings of The 11th International Conference on Learning Representations </i>. ICLR 2023.'
---
[[PDF]](https://richielo.github.io/files/RL_MARL_CTDU_ICLR_23.pdf)

## Abstract
By enabling agents to communicate, recent cooperative multi-agent reinforcement learning (MARL) methods have demonstrated better task performance and more coordinated behavior. Most existing approaches facilitate inter-agent communication by allowing agents to send messages to each other through free communication channels, i.e., cheap talk channels. Current methods require these channels to be constantly accessible and known to the agents a priori. In this work, we lift these requirements such that the agents must discover the cheap talk channels and learn how to use them. Hence, the problem has two main parts: cheap talk discovery (CTD) and cheap talk utilization (CTU). We introduce a novel conceptual framework for both parts and develop a new algorithm based on mutual information maximization that outperforms existing algorithms in CTD/CTU settings. We also release a novel benchmark suite to stimulate future research in CTD/CTU.