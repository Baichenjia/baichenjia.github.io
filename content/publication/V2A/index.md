---
title: "Unifying Value Alignment and Assignment in Cross-Domain Offline Reinforcement Learning with Heterogeneous Datasets"
authors:
  - Zhongjian Qiao
  - Jiafei Lyu
  - Chenjia Bai
  - Peisong Wang
  - Siyang Gao
  - Shuang Qiu
author_notes:
date: "2026-05-24T00:00:00Z"
doi: ""

draft: false

weight: 67
publishDate: "2026-05-24T00:00:00Z"

publication_types: ["conference"]
publication: "In *International Conference on Machine Learning (**ICML**)*, 2026"
publication_short: ""

abstract: >-
  Cross-domain offline reinforcement learning (RL) aims to learn a policy in the
  target domain with a limited target-domain dataset and a source-domain dataset
  that exhibits a dynamics shift. Training directly on the original source
  dataset typically leads to performance collapse. Recent studies perform data
  filtering from the perspective of dynamics alignment or value alignment to
  enable efficient policy transfer. However, these studies are typically
  validated on single-domain or single-behavior-policy source datasets. In this
  work, we explore a more general heterogeneous cross-domain offline RL setting,
  where the source datasets may be collected from multiple source domains by
  diverse behavior policies. We first uncover a critical yet overlooked issue in
  this setting: value misassignment. Empirically and theoretically, we
  demonstrate that value misassignment can undermine value alignment, mislead
  data filtering toward selecting suboptimal samples, and loosen the
  suboptimality gap, thereby degrading the agent's performance. To address this
  issue, we propose V2A, which integrates dynamics alignment, value alignment,
  and value assignment. V2A first employs temporally-consistent modality
  representation learning to extract dynamics modalities from the source dataset,
  followed by modality-aware advantage learning to rectify value alignment.
  Finally, it adopts a data filtering paradigm to selectively share source data
  for policy learning. Empirical results show that V2A significantly
  outperforms strong baseline methods under general heterogeneous cross-domain
  offline RL settings.

summary: V2A unifies dynamics alignment, value alignment, and value assignment for heterogeneous cross-domain offline RL and improves robust source-data filtering.

tags: []
featured: true

url_pdf: https://arxiv.org/abs/2605.24862
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_wechat: ''

image:
  caption: 'Image credit: Chenjia Bai'
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
