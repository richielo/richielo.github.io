---
title: "A Two-Stage Approach for Automated Prostate Lesion Detection and Classification with Mask R-CNN and Weakly Supervised Deep Neural Network"
collection: publications
permalink: /publication/Prostate_NN_MICCAI_WS_19
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2019-10-17
venue: 'MICCAI-19 Workshop on Artificial Intelligence in Radiation Therapy'
paperurl: 'http://richielo.github.io/files/Prostate_NN_MICCAI_WS_19.pdf'
citation: 'Liu, Zhiyu, Wenhao Jiang, Kit Hang Lee, <b>Yat Long Lo</b>, Yui Lun Ng, Qi Dou, Varut Vardhanabhuti and Ka Wai Kwok. <i>MICCAI Workshop on Artificial Intelligence in Radiation Therapy</i>. 2019'
---
[[PDF]](http://richielo.github.io/files/Prostate_NN_MICCAI_WS_19.pdf)

## Abstract
Early diagnosis of prostate cancer is very crucial to reduce the mortality rate. Multi-parametric magnetic resonance imaging (MRI) can provide detailed visualization of prostate tissues and lesions. Their malignancy can be diagnosed before any necessary invasive approaches, such as needle biopsy, at the risk of damage to or inflammation of the periprostatic nerves, prostate and bladder neck. However, the prostate tissue malignancy on magnetic resonance (MR) images can also be difficult to determine, with often inconclusive results among the clinicians. With the progress in artificial intelligence (AI), research on MR image-based lesion classification with AI tools are being explored increasingly. So far, existing classification approaches heavily rely on manually labelling of lesion areas, which is a labor-intensive and time-consuming process.

In this paper, we present a novel two-stage method for fully-automated prostate lesion detection and classification, using input sequences of T2-weighted images, apparent diffusion coefficient (ADC) maps and high b-value diffusion weighted images. In the first stage, a Mask R-CNN model is trained to automatically segment prostate structures. In the second stage, a weakly supervised deep neural network is developed to detect and classify lesions in a single run. To validate the accuracy of our system, we tested our method on two datasets, one from the PROSTATEx Challenge and the other from our local cohort. Our method can achieve average area-under-the-curve (AUC) of 0.912 and 0.882 on the two datasets respectively. The proposed approach present a promising tool for radiologists in their clinical practices.
