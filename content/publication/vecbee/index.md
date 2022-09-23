---
publication_types:
  - "2"
authors:
  - admin
  - Chang Meng
  - Fan Yang
  - Xiaolong Shen
  - Leibin Ni
  - Wei Wu
  - Zhihang Wu
  - Junfeng Zhao
  - Weikang Qian
abstract: Approximate computing is an emerging strategy to improve the energy efficiency of many error-tolerant applications. To design approximate circuit automatically, many approximate logic synthesis (ALS) methods have been proposed, among which many are greedy. To improve the synthesis quality of these greedy methods, one key is to calculate the errors of all candidate approximate transformations accurately. However, the traditional simulation-based method is time-consuming. Instead, many existing methods just perform quick but inaccurate error estimation. In this work, to improve both the accuracy and runtime of error estimation, we propose VECBEE, a versatile efficiency-accuracy configurable batch error estimation method for greedy ALS. It is based on Monte Carlo simulation and an efficient technique to capture whether a signal change due to an introduced approximation will be propagated to each primary output. VECBEE is generally applicable to any statistical error measurement, such as error rate and average error magnitude, and any graph-based circuit representation. It allows a flexible trade-off between the error estimation accuracy and the runtime, while even the fully accurate version is much faster than the traditional simulation-based method. We apply VECBEE to two representative greedy ALS methods and demonstrate its effectiveness in generating better approximate circuits. The code of VECBEE is made open-source.
url_pdf: "https://ieeexplore.ieee.org/document/9706238"
url_dataset: ""
url_project: ""
publication_short: In IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems
url_source: "https://github.com/SJTU-ECTL/VECBEE"
url_video: ""
title: VECBEE A Versatile Efficiency-Accuracy Configurable Batch Error Estimation Method for Greedy Approximate Logic Synthesis
featured: false
tags: []
projects:
date: 2022-05-22T00:00:00.000Z
url_slides: ""
publishDate: 2022-05-22T00:00:00.000Z
url_poster: ""
url_code: ""
doi: ""
---