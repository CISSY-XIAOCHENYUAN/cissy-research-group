---
title: "RBA-GCN: Relational Bilevel Aggregation Graph Convolutional Network for Emotion Recognition"
date: 2023-7-9
publishDate: 2023-07-09T05:19:01.168341Z
authors: 
- "Lin Yuan"
- "Guoheng Huang"
- "Fenghuan Li"
- "admin"
- "Chi-Man Pun"
- "Guo Zhong"
author_notes:
- ""
- "corresponding author"
- ""
- "corresponding author"
- ""
- "corresponding author"
publication_types: ["2"]
abstract: "Emotion recognition in conversation (ERC) has received increasing attention from researchers due to its wide range of applications. As conversation has a natural graph structure, numerous approaches used to model ERC based on graph convolutional networks (GCNs) have yielded significant results. However, the aggregation approach of traditional GCNs suffers from the node information redundancy problem, leading to node discriminant information loss. Additionally, single-layer GCNs lack the capacity to capture long-range contextual information from the graph. Furthermore, the majority of approaches are based on textual modality or stitching together different modalities, resulting in a weak ability to capture interactions between modalities. To address these problems, we present the relational bilevel aggregation graph convolutional network (RBA-GCN), which consists of three modules: the graph generation module (GGM), similarity-based cluster building module (SCBM) and bilevel aggregation module (BiAM). First, GGM constructs a novel graph to reduce the redundancy of target node information. Then, SCBM calculates the node similarity in the target node and its structural neighborhood, where noisy information with low similarity is filtered out to preserve the discriminant information of the node. Meanwhile, BiAM is a novel aggregation method that can preserve the information of nodes during the aggregation process. This module can construct the interaction between different modalities and capture long-range contextual information based on similarity clusters. On both the IEMOCAP and MELD datasets, the weighted average F1 score of RBA-GCN has a 2.17 to 5.21% improvement over that of the most advanced method."
featured: false
publication: "in *IEEE/ACM Transactions on Audio, Speech, and Language Processing* [SCI,JCR Q1]"
doi: "10.1109/TASLP.2023.3284509"
---
