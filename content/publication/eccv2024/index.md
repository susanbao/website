---
abstract: In this study, we investigate the task of active testing for label-efficient evaluation, which aims to estimate a model's performance on an unlabeled test dataset with a limited annotation budget. Previous approaches relied on deep ensemble models to identify highly informative instances for labeling, but fell short in dense recognition tasks like segmentation and object detection due to their high computational costs. In this work, we present MetaAT, a simple yet effective approach that adapts a Vision Transformer as a Meta Model for active testing. Specifically, we introduce a region loss estimation head to identify challenging regions for more accurate and informative instance acquisition. More importantly, the design of MetaAT allows it to handle annotation granularity at the region level, significantly reducing annotation costs in dense recognition tasks. As a result, our approach demonstrates consistent and substantial performance improvements over five popular benchmarks compared with state-of-the-art methods. Notably, on the CityScapes dataset, MetaAT achieves a 1.36% error rate in performance estimation using only 0.07% of annotations, marking a 10X improvement over existing state-of-the-art methods. To the best of our knowledge, MetaAT represents the first framework for active testing of dense recognition tasks.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - admin
  - Xin Li
  - Thang Doan
  - Sima Behpour
  - Wenbin He
  - Liang Gou
  - Fei Miao
  - Liu Ren
author_notes: []
publication: ""
summary: ""
url_dataset: ""
url_project: ""
publication_short: In 2024 European Conference on Computer Vision
url_source: ""
url_video: ""
title: "MetaAT: Active Testing for Label-Efficient Evaluation of Dense Recognition Tasks"
doi: ""
featured: false
tags: []
projects:
  - uncertainty-quantification-on-collaborative-perception
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: ./feature.PNG
date: 2024-07-18T23:29:00.499Z
url_slides: ""
publishDate: #2022-09-22T23:29:00.499Z
url_poster: ""
url_code: ""
---


