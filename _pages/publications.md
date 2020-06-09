---
layout: archive
title: "Publications [(Google Scholar Profile)](https://scholar.google.com/citations?user=qBM2A3kAAAAJ&hl=en)"
permalink: /publications/
author_profile: true
---
<br>
<b>[Improving Performance in Reinforcement Learning by Breaking Generalization in Neural Networks](https://richielo.github.io/publications/RL_BG_NN_AAMAS_20)</b><br>
Ghiassian, Sina, Banafsheh Rafiee, <b>Yat Long Lo</b>, Adam White. <i>In Proceedings of the 19th International Conference on Autonomous Agents and Multi-Agent Systems</i>. <b>AAMAS 2020</b>.

<b>[The Necessary Roadblock to Artificial General Intelligence: Corrigibility](https://richielo.github.io/publication/Corrigibility_AGI_SIGAI_19)</b><br>
<b>Lo, Yat Long</b>, Chung Yu Woo, and Ka Lok Ng. The Necessary Roadblock to Artificial General Intelligence: Corrigibility. <i>AI Matters</i>. 2019. <b> <span style="color:red">(Winner of 2018 ACM SIGAI Student Essay Contest on Artificial Intelligence Technologies)</span> </b>

<b>[Overcoming Catastrophic Interference in Online Reinforcement Learning with Dynamic Self-Organizing Maps](https://richielo.github.io/publication/RL_DSOM_NEURIPS_WS_19)</b><br>
<b>Lo, Yat Long</b> and Sina Ghiassian. <i>NeurIPS Workshop on Biological and Artificial Reinforcement Learning </i>. 2019.

<b>[A Two-Stage Approach for Automated Prostate Lesion Detection and Classification with Mask R-CNN and Weakly Supervised Deep Neural Network](https://richielo.github.io/publication/Prostate_NN_MICCAI_WS_19)</b><br>
Liu, Zhiyu, Wenhao Jiang, Kit Hang Lee, <b>Yat Long Lo</b>, Yui Lun Ng, Qi Dou, Varut Vardhanabhuti and Ka Wai Kwok. <i>MICCAI Workshop on Artificial Intelligence in Radiation Therapy</i>. 2019

<b>[Finding by counting: a probabilistic packet count model for indoor localization in ble environments](https://richielo.github.io/publication/BT_WNTECH_WS_17)</b><br>
De, Subham, Shreyans Chowdhary, Aniket Shirke, <b>Yat Long Lo</b>, Robin Kravets, and Hari Sundaram. <i>In Proceedings of the 11th Workshop on Wireless Network Testbeds, Experimental evaluation & Characterization, pp. 67-74. ACM </i>, 2017.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
