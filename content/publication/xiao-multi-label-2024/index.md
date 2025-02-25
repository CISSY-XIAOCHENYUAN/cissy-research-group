---
title: 'Multi-Label Chest X-Ray Image Classification With Single Positive Labels'
authors:
- Jiayin Xiao
- Si Li
- Tongxu Lin
- Jian Zhu
- admin
- David Dagan Feng
- Bin Sheng
author_notes:
- ""
- ""
- ""
- ""
- ""
- ""
- ""
date: '2024-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *IEEE Transactions on Medical Imaging* [SCI,JCR Q1]'
doi: 10.1109/TMI.2024.3421644
abstract: |
  <div class="justify-align"> Deep learning approaches for multi-label Chest X-ray (CXR) images classification usually require large-scale datasets. However, acquiring such datasets with full annotations is costly, time-consuming, and prone to noisy labels. Therefore, we introduce a weakly supervised learning problem called Single Positive Multi-label Learning (SPML) into CXR images classification (abbreviated as SPML-CXR), in which only one positive label is annotated per image. A simple solution to SPML-CXR problem is to assume that all the unannotated pathological labels are negative, however, it might introduce false negative labels and decrease the model performance. To this end, we present a Multi-level Pseudo-label Consistency (MPC) framework for SPML-CXR. First, inspired by the pseudo-labeling and consistency regularization in semi-supervised learning, we construct a weak-to-strong consistency framework, where the model prediction on weakly-augmented image is treated as the pseudo label for supervising the model prediction on a strongly-augmented version of the same image, and define an Image-level Perturbation-based Consistency (IPC) regularization to recover the potential mislabeled positive labels. Besides, we incorporate Random Elastic Deformation (RED) as an additional strong augmentation to enhance the perturbation. Second, aiming to expand the perturbation space, we design a perturbation stream to the consistency framework at the feature-level and introduce a Feature-level Perturbation-based Consistency (FPC) regularization as a supplement. Third, we design a Transformer-based encoder module to explore the sample relationship within each mini-batch by a Batch-level Transformer-based Correlation (BTC) regularization. Extensive experiments on the CheXpert and MIMIC-CXR datasets have shown the effectiveness of our MPC framework for solving the SPML-CXR problem. </div>
tags:
- Transformers
- Image classification
- Perturbation methods
- Chest X-ray classification
- Weakly supervised learning
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10579876
---
