---
title: 'LCCDMamba: Visual State Space Model for Land Cover Change Detection of VHR Remote Sensing Images'
authors:
- admin-JunqingHuang
- admin
- Chan-Tong Lam
- Yapeng Wang
- Min Xia
author_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
date: '2025-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*  [SCI, JCR Q1]'
doi: 10.1109/JSTARS.2025.3531499
abstract: <div class="justify-align">
  Land cover change detection (LCCD) is a crucial research topic for rational planning of land use and facilitation of sustainable land resource growth. However, due to the complexity of LCCD tasks, integrating global and local features and fusing contextual information from remote sensing features are essential. Recently, with the advent of Mamba, which maintains linear time complexity and high efficiency in processing long-range data, it offers a new solution to address feature-fusion challenges in LCCD. Therefore, a novel Visual State Space Model (SSM) for Land Cover Change Detection (LCCDMamba) is proposed, which uses Siam-VMamba as a backbone to extract multidimensional land cover features. To fuse the change information across difference temporal, Multi-scale Information Spatio-temporal Fusion (MISF) module is designed to aggregate difference information from bi-temporal features. The proposed MISF comprises Multi-Scale Feature Aggregation (MSFA) which utilizes strip convolution to aggregate multi-scale local change information of bi-temporal land cover features, and Residual with SS2D (RSS) which employs residual structure with SS2D to capture global feature differences of bi-temporal land cover features. To enhance the correlation of change features across different dimensions, in the Decoder, we design a Dual Token Modeling SSM (DTMS) through two token modeling approaches. This preserves high-dimensional semantic features and thus ensures that the multi-scale change information across various dimensions will not be lost during feature restoration. Experiments have been conducted on WHU-CD, LEVIR-CD, and GVLM datasets, and the results demonstrate that LCCDMamba achieves F1 scores of 94.18%, 91.68%, and 87.14%, respectively, outperforming all the models compared.
  </div>
tags:
- Remote sensing
- Land cover change detection
- VHR images
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10845192
---
