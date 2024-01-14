---
title: Triangular Chain Closed-Loop Detection Network for Dense Pedestrian Detection
authors:
- Qishen Yuan
- Guoheng Huang
- Guo Zhong
- admin
- Zhe Tan
- Zeng Lu
- Chi-Man Pun
author_notes:
- ""
- "corresponding author"
- ""
- ""
- ""
- ""
- ""
date: '2024-01-01'
publishDate: '2024-01-12T13:25:46.877208Z'
publication_types:
- article-journal
publication: 'in *IEEE Transactions on Instrumentation and Measurement* [SCI,JCR Q1]'
doi: 10.1109/TIM.2023.3341131
abstract: <div class="justify-align">
  Pedestrian detection has become an important topic in applications such as automatic driver assistance systems for automobiles and pedestrian tracking in surveillance systems, and many powerful object detectors have been widely used in smart sensing instruments. In realistic scenarios, pedestrians in image data are prone to overlap, and detection of fully bracketed boxes may still tend to be false positives in crowded scenes. In addition, low-level parameters shared among features during detection can cause mutual cancellation, resulting in a pair or set of head-enveloping boxes or body-enveloping boxes returning incorrect results. To address the above problems, we propose a triangular chain closed-loop detection network to improve detection in the case of body overlap. We propose a shared parameter elimination module to eliminate the interaction of shared low-level parameters, which has the advantage of improving the feature representation of occluded pedestrians and increasing feature utilization. Because the head bounding box detection encounters fewer occlusions in the occlusion case, the detection capability is better. Therefore, we propose a bidirectional matching module and a chain linking module to enhance the detection capability of the full bounding box using the head bounding box. These modules can better distinguish pedestrians in our network by focusing on individual region features on the pedestrian body, and then learn more representative pedestrian features by minimizing the vector similarity of the whole body, visible region, and head features in space. Our model has been extensively experimented on two challenging dense pedestrian datasets, CrowdHuman and Citypersons. Compared with the experimental results, our method achieves the best performance, especially on heavily occluded subsets, compared with o other popular existing technical methods. This method achieved good results on the CrowdHuman dataset, with an averaged precision (AP) improvement ...
  </div>
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10352356/
---
