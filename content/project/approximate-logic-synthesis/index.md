---
title: Approximate Logic Synthesis
date: 2022-09-23T01:28:26.966Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Recently, much attention has been paid to approximate computing, a novel design paradigm for error-tolerant applications. It can significantly reduce area, power consumption and delay of circuits by introducing an acceptable amount of error. Approximate logic synthesis (ALS) is an important field of it. We propose two novel methods for two-level ALS and multi-level ALS, respectively.



In terms of two-level ALS, we designed a novel heuristic algorithm to identify an approximate sum-of-product expression under a given error rate constraint so that it has the fewest literals. <strong>Outcomes</strong>: Through experiments with C++, we proved our algorithm is better than the previous state-of-the-art.



In terms of multi-level ALS, we designed a novel batch error estimation method based on Monte Carlo simulation and local change propagation to improve the performance of existing multi-level approximate logic synthesis flows. <strong>Outcomes</strong>: Through experiments with C++, under the average error magnitude, it achieves an improvement of 2.3x in area.
