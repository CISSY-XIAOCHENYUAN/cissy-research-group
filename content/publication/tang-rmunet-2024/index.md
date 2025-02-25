---
title: 'RM-UNet: UNet-like Mamba with Rotational SSM Module for Medical Image Segmentation'
authors:
- Hao Tang
- Guoheng Huang
- Lianglun Cheng
- admin
- Qi Tao
- Xuhang Chen
- Guo Zhong
- Xiaohui Yang
author_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
- ""
- "corresponding author"
- "corresponding author"
date: '2024-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *Signal, Image and Video Processing* [SCI,JCR Q3]'
doi: 10.1007/s11760-024-03484-8
abstract: |
  <div class="justify-align"> Accurate segmentation of tissues and lesions is crucial for disease diagnosis, treatment planning, and surgical navigation. Yet, the complexity of medical images presents significant challenges for traditional Convolutional Neural Networks and Transformer models due to their limited receptive fields or high computational complexity. State Space Models (SSMs) have recently shown notable vision performance, particularly Mamba and its variants. However, their feature extraction methods may not be sufficiently effective and retain some redundant structures, leaving room for parameter reduction. In response to these challenges, we introduce a methodology called Rotational Mamba-UNet, characterized by Residual Visual State Space (ResVSS) block and Rotational SSM Module. The ResVSS block is devised to mitigate network degradation caused by the diminishing efficacy of information transfer from shallower to deeper layers. Meanwhile, the Rotational SSM Module is devised to tackle the challenges associated with channel feature extraction within State Space Models. Finally, we propose a weighted multi-level loss function, which fully leverages the outputs of the decoder’s three stages for supervision. We conducted experiments on ISIC17, ISIC18, CVC-300, Kvasir-SEG, CVC-ColonDB, Kvasir-Instrument datasets, and Low-grade Squamous Intraepithelial Lesion datasets provided by The Third Affiliated Hospital of Sun Yat-sen University, demonstrating the superior segmentation performance of our proposed RM-UNet. Additionally, compared to the previous VM-UNet, our model achieves a one-third reduction in parameters. Our code is available at https://github.com/Halo2Tang/RM-UNet. </div>
tags:
- U-Net
- State Space Models
- Medical image segmentation
- Mamba
links:
- name: URL
  url: https://link.springer.com/article/10.1007/s11760-024-03484-8
---
