---
title: "Cross-Domain Offline Policy Adaptation with Dynamics- and Value-Aligned Data Filtering"
authors:
- Zhongjian Qiao
- Rui Yang
- Jiafei Lyu
- Chenjia Bai
- Xiu Li
- Zhuoran Yang
- Siyang Gao
- Shuang Qiu

author_notes:
date: "2025-12-02T00:00:00Z"
doi: ""
draft: false

weight: 62

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-02T00:00:00Z"

# Publication type.
publication_types: ["journal"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2512.02435"
publication_short: ""

abstract: Cross-Domain Offline Reinforcement Learning aims to train an agent deployed in the target environment, leveraging both a limited target domain dataset and a source domain dataset with possibly sufficient data coverage. Due to the underlying dynamics misalignment between the source and target domain, simply merging the data from two datasets may incur inferior performance. Recent advances address this issue by selectively sharing source domain samples that exhibit dynamics alignment with the target domain. However, these approaches focus solely on dynamics alignment and overlook value alignment, i.e., selecting high-quality, high-value samples from the source domain. In this paper, we first demonstrate that both dynamics alignment and value alignment are essential for policy learning, by examining the limitations of the current theoretical framework for cross-domain RL and establishing a concrete sub-optimality gap of a policy trained on the source domain and evaluated on the target domain. Motivated by the theoretical insights, we propose to selectively share those source domain samples with both high dynamics and value alignment and present our Dynamics- and Value-aligned Data Filtering (DVDF) method. We design a range of dynamics shift settings, including kinematic and morphology shifts, and evaluate DVDF on various tasks and datasets, as well as in challenging extremely low-data settings where the target domain dataset contains only 5,000 transitions. Extensive experiments demonstrate that DVDF consistently outperforms prior strong baselines and delivers exceptional performance across multiple tasks and datasets.

summary: We propose DVDF, a method for cross-domain offline RL that filters source data by both dynamics and value alignment, achieving strong performance in challenging settings.

tags: []
featured: true

url_pdf: https://arxiv.org/abs/2512.02435
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
