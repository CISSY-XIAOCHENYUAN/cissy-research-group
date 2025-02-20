---
title: 'TCIA: A Transformer-CNN Model With Illumination Adaptation for Enhancing Cell Image Saliency and Contrast'
authors:
- Jietao Yang
- Guoheng Huang
- Yanzhang Luo
- Xiaofeng Zhang
- admin
- Xuhang Chen
- Chi-Man Pun
- Mu-Yan Cai
author_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
- ""
- ""
- ""
date: '2025-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *IEEE Transactions on Instrumentation and Measurement* [SCI,JCR Q1]'
doi: 10.1109/TIM.2025.3527542
abstract: <div class="justify-align">
 Inconsistent illumination across imaging instruments poses significant challenges for accurate cell detection and analysis. Conventional methods (e.g., histogram equalization and basic filtering) struggle to adapt to complex lighting conditions, resulting in limited image enhancement and inconsistent performance. To address these issues, we propose the transformer-convolutional neural network (CNN) model with illumination adaptation (TCIA) model, which improves cell image saliency and contrast. By extracting illumination invariant features (IIF) using a locally sensitive histogram as prior knowledge, our model effectively adapts to varying illumination conditions. The TCIA framework employs hybrid convolution blocks (HCBs) to extract and preserve essential features from image pairs, followed by a two-branch decomposition-fusion network that separates features into low-frequency and high-frequency components. The Lite-Transformer (LT) captures global context for low-frequency features, while the circular difference invertible (CDI) module focuses on fine-grained textures and edges for high-frequency features. These features are then fused and reconstructed to produce high-contrast, salient images. Extensive experiments on three datasets (MoNuSeg, MoNuSAC, and our contributed MTGC) demonstrate that TCIA outperforms existing methods in image fusion and cell detection, achieving an average improvement in detection accuracy of 2%. This work provides a robust and innovative solution for enhanced cell imaging, contributing to more precise diagnostics and analysis. The source code will be available at https://github.com/Mrzhans/TCIA.
 </div>
tags:
- Feature extraction
- Cell image enhancement
- Illumination-adaptive
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10835409
---
