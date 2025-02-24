---
title: 'Image Manipulation Localization Using Dual-Shallow Feature Pyramid Fusion and Boundary Contextual Incoherence Enhancement'
authors:
- admin-YanXiang
- admin
- admin-KaiqiZhao
- admin-TongLiu
- admin-ZhiyaoXie
- Guoheng Huang
- Jianqing Li
author_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
- ""
- ""
date: '2024-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *IEEE Transactions on Emerging Topics in Computational Intelligence* [SCI,JCR Q1]'
doi: 10.1109/TETCI.2024.3500025
abstract: |
  <div class="justify-align"> This paper proposes a novel end-to-end network for Image Manipulation Localization (IML) comprising three modules: feature fusion, encoder, and decoder. To address the limitations of current DNN-based IML algorithms in accessing global features and segmenting tampered edges, we propose a Dual-shallow Feature Pyramid Fusion (DFPF) module. The DFPF module integrates semantic and texture features through a bidirectional pathway, forming RGB Feature Pyramids (RGBFP) and Local Textual Feature Pyramids (LTFP) using dual Hybrid ResNet50s in a ’Siamese' configuration. These feature pyramids are merged via multi-scale fusion to enhance global pyramid features for decoding. The LTFP branch includes a Pre-processing Block, Parallel Multi-Scale Convolution (PMSC), or Channel Split High-frequency Convolution (CSHC) to capture local textual features and subtle manipulation traces. The Encoder employs Transformer layers for robust global representations. At the same time, the Decoder uses Cascaded Boundary Context Inconsistent Enhancement (BCIE) Blocks to reconstruct a coarse-to-fine binary mask, enhancing texture inconsistencies at manipulated region boundaries. Additionally, we introduce an automated method for generating a large-scale forgery dataset via Photoshop Scripting, reducing labor costs. Our model effectively locates tampered regions of various shapes and sizes, improving boundary anomaly detection. Extensive experimental results demonstrate that our method significantly outperforms existing state-of-the-art models. </div>
tags:
- Feature extraction
- Decoding
- Edge detection
- Image manipulation localization (IML)
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10771742
---
