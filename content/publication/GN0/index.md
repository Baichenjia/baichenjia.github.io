---
title: "GN0: Toward a Unified Paradigm for Generation, Evaluation, and Policy Learning in Visual-Language Navigation"
authors:
  - Xinhai Li
  - Xiaotao Zhang
  - Yuehao Huang
  - Jiankun Dong
  - Tianhang Wang
  - Sunyao Zhou
  - Yunzi Wu
  - Chengnuo Sun
  - Yunfei Ge
  - Qizhen Weng
  - Chi Zhang
  - Chenjia Bai*
  - Xuelong Li*
author_notes:
date: "2026-06-02T00:00:00Z"
doi: ""

draft: false

weight: 79

publishDate: "2026-06-02T00:00:00Z"

publication_types: ["preprint"]

publication: "arXiv preprint"
publication_short: ""

abstract: "Embodied navigation connects intelligent agents with the physical world and is fundamental for general robotic intelligence. Limited availability and quality of navigation data have constrained Vision-and-Language Navigation (VLN) systems' generalization and long-horizon capabilities. To address this, we curate diverse 3D scenes and develop an automated pipeline for large-scale navigation data, resulting in the GN-Matrix dataset. Building on a 3D Gaussian Splatting (3DGS) engine, we introduce a high-fidelity simulation platform supporting interactive roaming and collision-aware navigation. We further propose GN-Bench, the first BEV-based benchmark incorporating dynamic 3DGS avatars for human-robot interaction evaluation. To leverage the simulator, we develop an RL-driven navigation foundation model, Break and Establish (BAE). After supervised learning, DAgger exposes the model to rollout-induced states, breaking narrow expert-centric distributions and enabling downstream RL exploration. This unified VLN paradigm integrates map-based and map-free tasks, including instruction following, human following, and goal navigation. GN-BAE formalizes high-fidelity 3DGS-rendered Bird's Eye View representations as compact memory, unlocking latent spatial reasoning in VLMs. Extensive evaluations on GN-Bench and VLN-CE show that GN0 outperforms state-of-the-art VLN methods. Overall, GN-Matrix offers a unified framework spanning data, simulation, and learning, advancing embodied navigation in research and industrial applications."

summary: GN0 unifies GN-Matrix data generation, the high-fidelity GN-Bench simulator, and the RL-driven GN-BAE foundation model for map-based and map-free visual-language navigation.
tags: []

featured: true

url_pdf: 'https://arxiv.org/abs/2606.03682'
url_code: 'https://github.com/TeleHuman/GN0'
url_dataset: ''
url_poster: ''
url_project: 'https://telehuman-gn0.github.io/'
url_slides: ''
url_source: ''
url_video: ''
url_wechat: ''

links:
  - name: Models
    url: 'https://huggingface.co/TeleEmbodied/GN-BAE'

image:
  caption: 'Image credit: GN0 authors'
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
