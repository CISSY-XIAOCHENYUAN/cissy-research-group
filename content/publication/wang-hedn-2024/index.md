---
title: 'HEDN: Multi-Oriented Hierarchical Extraction and Dual-Frequency Decoupling Network for 3D Medical Image Segmentation'
authors:
- Yu Wang
- Guoheng Huang
- Zeng Lu
- Ying Wang
- Xuhang Chen
- admin
- Yan Li
- Jieni Liu
- Yingping Huang
author_notes:
- ""
- ""
- ""
- ""
- ""
- "corresponding author"
- ""
- ""
- ""
date: '2024-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *Medical & Biological Engineering & Computing* [SCI,JCR Q2]'
doi: 10.1007/s11517-024-03192-y
abstract: |
  <div class="justify-align"> Previous 3D encoder-decoder segmentation architectures struggled with fine-grained feature decomposition, resulting in unclear feature hierarchies when fused across layers. Furthermore, the blurred nature of contour boundaries in medical imaging limits the focus on high-frequency contour features. To address these challenges, we propose a Multi-oriented Hierarchical Extraction and Dual-frequency Decoupling Network (HEDN), which consists of three modules: Encoder-Decoder Module (E-DM), Multi-oriented Hierarchical Extraction Module (Multi-HEM), and Dual-frequency Decoupling Module (Dual-DM). The E-DM performs the basic encoding and decoding tasks, while Multi-HEM decomposes and fuses spatial and slice-level features in 3D, enriching the feature hierarchy by weighting them through 3D fusion. Dual-DM separates high-frequency features from the reconstructed network using self-supervision. Finally, the self-supervised high-frequency features separated by Dual-DM are inserted into the process following Multi-HEM, enhancing interactions and complementarities between contour features and hierarchical features, thereby mutually reinforcing both aspects. On the Synapse dataset, HEDN outperforms existing methods, boosting Dice Similarity Score (DSC) by 1.38% and decreasing 95% Hausdorff Distance (HD95) by 1.03 mm. Likewise, on the Automatic Cardiac Diagnosis Challenge (ACDC) dataset, HEDN achieves  0.5% performance gains across all categories. </div>
tags:
- 3D medical image segmentation
- Encoder-decoder architecture
- Multi-oriented hierarchical extraction
- Dual-frequency decoupling
links:
- name: URL
  url: https://link.springer.com/article/10.1007/s11517-024-03192-y
---
