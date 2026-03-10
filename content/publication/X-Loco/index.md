---
title: "X-Loco: Towards Generalist Humanoid Locomotion Control via Synergetic Policy Distillation"
authors:
  - Dewei Wang
  - Xinmiao Wang
  - Chenyun Zhang
  - Jiyuan Shi
  - Yingnan Zhao
  - Chenjia Bai*
  - Xuelong Li
author_notes:
date: "2026-03-04T00:00:00Z"
doi: ""

weight: 67
publishDate: "2026-03-04T00:00:00Z"

publication_types: ["preprint"]
publication: "arXiv preprint"
publication_short: ""
abstract: While recent advances have demonstrated strong performance in individual humanoid skills such as upright locomotion, fall recovery and whole-body coordination, learning a single policy that masters all these skills remains challenging due to the diverse dynamics and conflicting control objectives involved. To address this, we introduce X-Loco, a framework for training a vision-based generalist humanoid locomotion controller. The key insight is that the fundamental locomotion skills of standing up, recovering from falls, walking, running, and jumping share a common latent representation. We propose a novel policy distillation approach that synergistically transfers knowledge from independently trained expert policies into a single multi-skills policy. To tackle the conflicting objectives arising from distinct skill dynamics, we introduce a skill-conditioned adaptive loss weighting mechanism that dynamically balances the optimization process. Additionally, we integrate a domain randomization strategy specifically tailored for the distillation process, enabling sim-to-real transfer without requiring any real-world fine-tuning. Extensive experiments demonstrate that our unified policy successfully masters diverse locomotion skills in both simulation and the real world.
summary: We introduce X-Loco, a framework for training a vision-based generalist humanoid locomotion controller through synergetic policy distillation.
tags: []
featured: true
url_pdf: https://arxiv.org/abs/2603.03733
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
image:
  caption: 'Image credit: Chenjia Bai'
  focal_point: ""
  preview_only: false
projects: []
slides: ""
---
