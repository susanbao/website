---
abstract: Object detection and multiple object tracking (MOT) are essential components of self-driving systems. Accurate detection and uncertainty quantification are both critical for onboard modules, such as perception, prediction, and planning, to improve the safety and robustness of autonomous vehicles. Collaborative object detection (COD) has been proposed to improve detection accuracy and reduce uncertainty by leveraging the viewpoints of multiple agents. However, little attention has been paid on how to leverage the uncertainty quantification from COD to enhance MOT performance. In this paper, as the first attempt, we design an uncertainty propagation framework to address this challenge, called MOT-CUP. Our framework first quantifies the uncertainty of COD through direct modeling and conformal prediction, and propagates this uncertainty information into the motion prediction and association steps. MOT-CUP is designed to work with different collaborative object detectors and baseline MOT algorithms. We evaluate MOT-CUP on V2X-Sim,  a comprehensive collaborative perception dataset, and demonstrate a 2% improvement in accuracy and a 2.67X reduction in uncertainty compared to the baselines, e.g. SORT and ByteTrack. In scenarios characterized by high occlusion levels, our MOT-CUP demonstrates a noteworthy $4.01\%$ improvement in accuracy. MOT-CUP demonstrates the importance of uncertainty quantification in both COD and MOT, and provides the first attempt to improve the accuracy and reduce the uncertainty in MOT based on COD through uncertainty propagation.
slides: ""
url_pdf: "https://arxiv.org/abs/2303.14346"
publication_types:
  - "2"
authors:
  - admin
  - Songyang Han
  - Yiming Li
  - Zhili Zhang
  - Chen Feng
  - Caiwen Ding
  - Fei Miao
author_notes: []
publication: ""
summary: ""
url_dataset: ""
url_project: "https://coperception.github.io/MOT-CUP/"
publication_short: In IEEE Robotics and Automation Letters
url_source: ""
url_video: ""
title: Collaborative Multi-Object Tracking with Conformal Uncertainty Propagation
doi: ""
featured: false
tags: []
projects:
  - uncertainty-quantification-on-collaborative-perception
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: ./feature.png
date: 2024-01-18T23:29:00.499Z
url_slides: ""
publishDate: #2022-09-22T23:29:00.499Z
url_poster: ""
url_code: "https://github.com/susanbao/mot_cup"
---


