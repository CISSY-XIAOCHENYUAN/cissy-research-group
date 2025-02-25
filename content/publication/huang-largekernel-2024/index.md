---
title: 'Large kernel convolution application for land cover change detection of remote sensing images'
authors:
- admin-JunqingHuang
- admin
- Chan-Tong Lam
- Wei Ke
- Guoheng Huang
author_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
date: '2024-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *International Journal of Applied Earth Observation and Geoinformation* [SCI,JCR Q1]'
doi: 10.1016/j.jag.2024.104077
abstract: |
  <div class="justify-align"> In land cover change detection tasks, extracting universal features of changing targets is crucial for achieving precise detection results. A larger receptive field helps the model capture these universal features of changing targets. Although Large Kernel Convolution has been widely used in the field of computer vision, its potential in land cover change detection of remote sensing images has not been fully explored. To address this, a novel Re-parameterization Large kernel Convolution Network for Change Detection (CD-RLKNet) is proposed. CD-RLKNet utilizes Spatial and Temporal Adaptive Fusion Module to preliminarily extract spatial–temporal features from bi-temporal remote sensing images, resulting in a coarse-grained fused feature map. Features Assimilation Assistant Module extracts independent features from land cover information of each temporal, serving as auxiliary information for fine-grained features. Bi-temporal Features Integration Module utilizes large kernel convolution to extract bi-temporal land cover features with a larger receptive field, capturing fine-grained differences in these features. Experiments have been conducted on SYSU-CD, LEVIR-CD and GVLM-CD datasets, and results show that the proposed CD-RLKNet achieves IoU values of 0.6882, 0.8294 and 0.7729, respectively, surpassing the compared SOTA models. The code of CD-RLKNet can be achieved from https://github.com/juncyan/cdrlknet.git. </div>
tags:
- Land cover
- Change detection
- Remote sensing
- Larger receptive field
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S156984322400431X
---
