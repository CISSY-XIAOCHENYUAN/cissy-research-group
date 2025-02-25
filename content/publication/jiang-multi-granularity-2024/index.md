---
title: 'Multi-Granularity Hypergraph-Guided Transformer Learning Framework for Visual Classification'
authors:
- Jianjian Jiang
- Ziwei Chen
- Fangyuan Lei
- Long Xu
- Jiahao Huang
- admin
author_notes:
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
publication: 'in *The Visual Computer* [SCI,JCR Q2]'
doi: 10.1007/s00371-024-03541-w
abstract: |
  <div class="justify-align"> Fine-grained single-label classification tasks aim to distinguish highly similar categories but often overlook inter-category relationships. Hierarchical multi-granularity visual classification strives to categorize image labels at various hierarchy levels, offering optimize label selection for people. This paper addresses the hierarchical multi-granularity classification problem from two perspectives: (1) effective utilization of labels at different levels and (2) efficient learning to distinguish multi-granularity visual features. To tackle these issues, we propose a novel multi-granularity hypergraph-guided transformer learning framework (MHTL), seamlessly integrating swin transformers and hypergraph neural networks for handling visual classification tasks. Firstly, we employ swin transformer as an image hierarchical feature learning (IHFL) module to capture hierarchical features. Secondly, a feature reassemble (FR) module is applied to rearrange features at different hierarchy levels, creating a spectrum of features from coarse to fine-grained. Thirdly, we propose a feature relationship mining (FRM) module, to unveil the correlation between features at different granularity. Within this module, we introduce a learnable hypergraph modeling method to construct coarse to fine-grained hypergraph structures. Simultaneously, multi-granularity hypergraph neural networks are employed to explore grouping relationships across different granularities, thereby enhancing the learning of semantic feature representations. Finally, we adopt a multi-granularity classifier (MC) to predict hierarchical label probabilities. Experimental results demonstrate that MHTL outperforms other state-of-the-art classification methods across three multi-granularity datasets. The source code and models are released at https://github.com/JJJTF/MHTL. </div>
tags:
- Hierarchical multi-granularity
- Visual classification
- Hypergraph neural network
- Swin transformer
links:
- name: URL
  url: https://link.springer.com/article/10.1007/s00371-024-03541-w
---
