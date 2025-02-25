---
title: 'Weakly supervised semantic segmentation via saliency perception with uncertainty-guided noise suppression'
authors:
- Xinyi Liu
- Guoheng Huang
- admin
- Zewen Zheng
- Guo Zhong
- Xuhang Chen
- Chi-Man Pun
author_notes:
- ""
- "corresponding author"
- "corresponding author"
- ""
- ""
- ""
- ""
date: '2024-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *The Visual Computer* [SCI,JCR Q2]'
doi: 10.1007/s00371-024-03574-1
abstract: |
  <div class="justify-align"> Weakly Supervised Semantic Segmentation (WSSS) has become increasingly popular for achieving remarkable segmentation with only image-level labels. Current WSSS approaches extract Class Activation Mapping (CAM) from classification models to produce pseudo-masks for segmentation supervision. However, due to the gap between image-level supervised classification loss and pixel-level CAM generation tasks, the model tends to activate discriminative regions at the image level rather than pursuing pixel-level classification results. Moreover, insufficient supervision leads to unrestricted attention diffusion in the model, further introducing inter-class recognition noise. In this paper, we introduce a framework that employs Saliency Perception and Uncertainty, which includes a Saliency Perception Module (SPM) with Pixel-wise Transfer Loss (SP-PT), and an Uncertainty-guided Noise Suppression method. Specifically, within the SPM, we employ a hybrid attention mechanism to expand the receptive field of the module and enhance its ability to perceive salient object features. Meanwhile, a Pixel-wise Transfer Loss is designed to guide the attention diffusion of the classification model to non-discriminative regions at the pixel-level, thereby mitigating the bias of the model. To further enhance the robustness of CAM for obtaining more accurate pseudo-masks, we propose a noise suppression method based on uncertainty estimation, which applies a confidence matrix to the loss function to suppress the propagation of erroneous information and correct it, thus making the model more robust to noise. We conducted experiments on the PASCAL VOC 2012 and MS COCO 2014, and the experimental results demonstrate the effectiveness of our proposed framework. Code is available at https://github.com/pur-suit/SPU. </div>
tags:
- Weakly Supervised Semantic Segmentation
- Class Activation Mapping
- Uncertainty estimation
- Attention mechanism
links:
- name: URL
  url: https://link.springer.com/article/10.1007/s00371-024-03574-1
---
