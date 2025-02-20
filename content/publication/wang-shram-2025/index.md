---
title: 'The Structure-sharing Hypergraph Reasoning Attention Module for CNNs'
authors:
- Jingchao Wang
- Guoheng Huang
- admin
- Guo Zhong
- Tongxu Lin
- Chi-Man Pun
- Fenfang Xie
authors_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
- ""
- ""
date: '2025-01-01'
publishDate: ''
publication_types:
- article-journal
publication: 'in *Expert Systems with Applications* [SCI,JCR Q1]'
doi: 10.1016/j.eswa.2024.125240
abstract: <div class="justify-align">Attention mechanisms improve the performance of models by selectively processing relevant information. However, existing attention mechanisms for CNNs do not utilize the high-order semantic similarity between different channels in the input when inferring attention. To address this issue, in this paper, we propose the Structure-sharing Hypergraph Reasoning Attention Module (SHRA Module) to explore the high-order similarity among nodes via hypergraph learning. SHRA Module transforms the input CNN feature maps into hypergraph node representations, which are used to reason attention under a set of learnable hypergraph convolutions. When performing the hypergraph convolution, the SHRA Module utilizes our proposed structure-sharing hypergraph convolution (SHGCN) to perform hypergraph convolutions, where the hypergraphs from different groups and the weight matrices for hypergraph convolutions are conducted in a right-shifted-permutation sequence of hypergraphs. As a result, the weights matrices can be shared with all groups of hypergraphs while performing hypergraph convolution, thus the global information can be used by the module to have a deep look into the input feature. We evaluate SHRA Module with models in object detection, lesion segmentation, and image classification tasks to demonstrate its effectiveness. Experimental results show that SHRA Module highly significantly enhances model performance, surpassing that of classic attention modules.</div>
tags:
- Attention mechanism
- Hypergraph
- Structure-sharing
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/abs/pii/S0957417424021079
---
