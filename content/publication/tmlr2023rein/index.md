---
publication_types:
  - "2"
authors:
  - Sihong He
  - Songyang Han
  - admin
  - Shuo Han
  - Shaofeng Zou
  - Fei Miao
abstract: In real-world multi-agent reinforcement learning (MARL) applications, agents may not have perfect state information (e.g., due to inaccurate measurement or malicious attacks), which challenges the robustness of agents' policies. Though robustness is getting important in MARL deployment, little prior work has studied state uncertainties in MARL, neither in problem formulation nor algorithm design. Motivated by this robustness issue and the lack of corresponding studies, we study the problem of MARL with state uncertainty in this work. We provide the first attempt to the theoretical and empirical analysis of this challenging problem. We first model the problem as a Markov Game with state perturbation adversaries (MG-SPA) by introducing a set of state perturbation adversaries into a Markov Game. We then introduce robust equilibrium (RE) as the solution concept of an MG-SPA. We conduct a fundamental analysis regarding MG-SPA such as giving conditions under which such a robust equilibrium exists. Then we propose a robust multi-agent Q-learning (RMAQ) algorithm to find such an equilibrium, with convergence guarantees. To handle high-dimensional state-action space, we design a robust multi-agent actor-critic (RMAAC) algorithm based on an analytical expression of the policy gradient derived in the paper. Our experiments show that the proposed RMAQ algorithm converges to the optimal value function; our RMAAC algorithm outperforms several MARL and robust MARL methods in multiple multi-agent environments when state uncertainty is present. 
url_pdf: "https://openreview.net/pdf?id=CqTkapZ6H9"
url_dataset: ""
url_project: ""
publication_short: Transactions on Machine Learning Research
url_source: ""
url_video: ""
title: Robust Multi-Agent Reinforcement Learning with State Uncertainty
featured: false
tags: []
projects:
  - learning-and-control-for-connected-autonomous-vehicles
date: 2023-06-28T00:00:00.000Z
url_slides: ""
publishDate: 2023-06-28T00:00:00.000Z
url_poster: ""
url_code: "https://github.com/sihongho/robust_marl_with_state_uncertainty"
doi: ""
---