---
title: "Lp-slam: language-perceptive RGB-D SLAM framework exploiting large language model"
collection: publications
category: manuscripts
permalink: /publication/lp_slam
excerpt: 'This paper is about the LLM employed in SLAM systems.'
date: 2024-4-30
venue: 'Complex \& Intelligent Systems'
paperurl: 'https://tenthousandrain.github.io/files/lp_slam.pdf'
---

Abstract
---
With the development of deep learning, a higher level of perception of the environment such as the semantic level can be achieved in the simultaneous localization and mapping (SLAM) domain. However, previous works did not achieve a natural-language level of perception. Therefore, LP-SLAM (Language-Perceptive RGB-D SLAM) is proposed that leverages large language models (LLMs). The texts in the scene can be detected by scene text recognition (STR) and mapped as landmarks with a task-driven selection. A text error correction chain (TECC) is designed with a similarity classification method, a two-stage memory strategy, and a text clustering method. The proposed architecture is designed to deal with the mis-detection and mis-recognition cases of STR and to provide accurate text information to the framework. The proposed framework takes input images and generates a 3D map with sparse point cloud and task-related texts. Finally, a natural user interface (NUI)is designed based on the constructed map and LLM, which gives position instructions based on users’ natural queries. The experimental results validated the proposed TECC design and the overall framework. We publish the virtual dataset with ground truth, as well as the [source code](https://github.com/GroupOfLPSLAM/LP_SLAM) for further research.

![Image Not Found](https://tenthousandrain.github.io/images/lp_frame.png)


[More information here](https://link.springer.com/article/10.1007/s40747-024-01408-0)
