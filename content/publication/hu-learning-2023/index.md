---
title: "Learning from Incorrectness: Active Learning with Negative Pre-training and Curriculum Querying for Histological Tissue Classification"
date: 2023-09-08
publishDate: 2023-09-08T07:49:33.682060Z
authors:
- "Wentao Hu"
- "Lianglun Cheng"
- "Guoheng Huang"
- "admin"
- "Guo Zhong"
- "Chi-Man Pun"
- "Jian Zhou"
- "Muyan Cai"
author_notes:
- ""
- ""
- ""
- ""
- ""
- ""
- ""
- ""
publication_types: ["2"]
abstract: "Patch-level histological tissue classification is an effective pre-processing method for histological slide analysis. However, the classification of tissue with deep learning requires expensive annotation costs. To alleviate the limitations of annotation budgets, the application of active learning (AL) to histological tissue classification is a promising solution. Nevertheless, there is a large imbalance in performance between categories during application, and the tissue corresponding to the categories with relatively insufficient performance are equally important for cancer diagnosis. In this paper, we propose an active learning framework called ICAL, which contains Incorrectness Negative Pre-training (INP) and Category-wise Curriculum Querying (CCQ) to address the above problem from the perspective of category-to-category and from the perspective of categories themselves, respectively. In particular, INP incorporates the unique mechanism of active learning to treat the incorrect prediction results that obtained from CCQ as complementary labels for negative pre-training, in order to better distinguish similar categories during the training process. CCQ adjusts the query weights based on the learning status on each category by the model trained by INP, and utilizes uncertainty to evaluate and compensate for query bias caused by inadequate category performance. Experimental results on two histological tissue classification datasets demonstrate that ICAL achieves performance approaching that of fully supervised learning with less than 16% of the labeled data. In comparison to the state-of-the-art active learning algorithms, ICAL achieved better and more balanced performance in all categories and maintained robustness with extremely low annotation budgets. The source code will be released at https://github.com/LactorHwt/ICAL."
featured: True
publication: "in *IEEE Transactions on Medical Imaging*  [SCI, JCR Q1]"
doi: "10.1109/TMI.2023.3313509"
---

