---
title: 'Psanet: Prototype-Guided Salient Attention for Few-Shot Segmentation'
authors:
- Hao Li
- Guoheng Huang
- admin
- Zewen Zheng
- Xuhang Chen
- Guo Zhong
- Chi-Man Pun
author_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
- "corresponding author"
- ""
date: '2024-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *The Visual Computer* [SCI,JCR Q2]'
doi: 10.1007/s00371-024-03582-1
abstract: |
  <div class="justify-align"> Few-shot semantic segmentation aims to learn a generalized model for unseen-class segmentation with just a few densely annotated samples. Most current metric-based prototype learning models utilize prototypes to assist in query sample segmentation by directly utilizing support samples through Masked Average Pooling. However, these methods frequently fail to consider the semantic ambiguity of prototypes, the limitations in performance when dealing with extreme variations in objects, and the semantic similarities between different classes. In this paper, we introduce a novel network architecture named Prototype-guided Salient Attention Network (PSANet). Specifically, we employ prototype-guided attention to learn salient regions, allocating different attention weights to features at different spatial locations of the target to enhance the significance of salient regions within the prototype. In order to mitigate the impact of external distractor categories on the prototype, our proposed contrastive loss has the capability to acquire a more discriminative prototype to promote inter-class feature separation and intra-class feature compactness. Moreover, we suggest implementing a refinement operation for the multi-scale module in order to enhance the ability to capture complete contextual information regarding features at various scales. The effectiveness of our strategy is demonstrated by extensive tests performed on the PASCAL-5<sup>i</sup> and COCO-20<sup>i</sup> datasets, despite its inherent simplicity. Our code is available at https://github.com/woaixuexixuexi/PSANet. </div>
tags:
- Semantic segmentation
- Few-shot segmentation
- Attention mechanism
- Contrastive learning
links:
- name: URL
  url: https://link.springer.com/article/10.1007/s00371-024-03582-1
---
