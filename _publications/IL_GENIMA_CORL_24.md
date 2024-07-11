---
title: "Generative Image as Action Models"
collection: publications
permalink: /publication/IL_GENIMA_CORL_24
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-01-31
venue: '<i>In Review</i>'
paperurl: 'https://richielo.github.io/files/IL_GENIMA_CORL_24.pdf'
citation: 'Mohit Shridhar*, <b>Lo, Yat Long*</b>, Stephen James. In Review.'
---
[[PDF]](https://richielo.github.io/files/IL_GENIMA_CORL_24.pdf)

## Abstract
Image-generation diffusion models have been fine-tuned to unlock new capabilities such as image-editing and novel view synthesis. Can we similarly unlock image-generation models for visuomotor control? We present GENIMA, a behavior-cloning agent that fine-tunes Stable Diffusion to 'draw joint-actions' as targets on RGB images. These images are fed into a controller that maps the visual targets into a sequence of joint-positions. We study GENIMA on 25 RLBench and 9 real-world manipulation tasks. We find that, by lifting actions into image-space, internet pre-trained diffusion models can generate policies that outperform state-of-the-art visuomotor approaches, especially in robustness to scene perturbations and generalizing to novel objects. Our method is also competitive with 3D agents, despite lacking priors such as depth, keypoints, or motion-planners.