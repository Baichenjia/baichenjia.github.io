---
title: "GN0: Toward a Unified Paradigm for Generation, Evaluation, and Policy Learning in Visual-Language-Navigation"
authors:
  - Xinhai Li
  - Xiaotao Zhang
  - Yuehao Huang
  - Jiankun Dong
  - Tianhang Wang
  - Sunyao Zhou
  - Yunzi Wu
  - Chenguo Sun
  - Yunfei Ge
  - Qizhen Weng
  - Chi Zhang
  - Chenjia Bai*
  - Xuelong Li*
author_notes:
date: "2025-01-01T00:00:00Z"
doi: ""

weight: 72

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]

# Publication name and optional abbreviated publication name.
publication: "Under Review. 2026"
publication_short: ""

abstract: "Embodied navigation connects intelligent agents with the physical world and serves as a fundamental capability for achieving general robotic intelligence. However, the availability and quality of navigation data have long limited the generalization ability of Vision-and-Language Navigation (VLN) systems and their capacity to handle long-horizon tasks. To bridge this gap, we curate diverse 3D scene resources and develop an automated pipeline for large-scale navigation data generation, resulting in the GN-Matrix dataset. Building upon a 3D Gaussian Splatting (3DGS) rendering engine, we further introduce a high-fidelity simulation platform that supports interactive roaming and collision-aware navigation. Furthermore, we propose GN-Bench, the first benchmark to provide BEV-based evaluation, incorporating dynamic 3DGS avatars to establish new standards for human-robot interaction evaluation. To fully leverage the interactive nature of the simulator, we develop an RL-driven navigation foundation model, Break and Establish (BAE)), after supervised learning, DAgger exposes the model to rollout-induced states and recovery behaviors beyond idealized offline demonstrations, breaking the narrow expert-centric distribution inherited from supervision and providing a better starting point for downstream RL exploration. This unified VLN paradigm seamlessly integrates both map-based and map-free settings, enabling a broad spectrum of tasks including instruction following, human following, and goal navigation. To the best of our knowledge, this work is the first to formalize high-fidelity 3DGS-rendered Bird’s Eye View (BEV) representations as a compact and efficient memory mechanism, thereby unlocking the latent spatial reasoning capabilities of Vision-and-Language Models (VLMs). The dual-system architecture of GN0 ensures both flexibility and high-efficiency deployment in real-world scenarios. Extensive evaluations on GN-Bench, encompassing both quantitative and qualitative analyses,demonstrate that the proposed GN0 significantly outperforms existing state-of-the-art VLN methods. Overall, this work, GN-Maxtrix, presents a unified framework spanning data, simulation, and learning, offering new insights for advancing embodied navigation in both academic research and industrial applications."

# Summary. An optional shortened abstract.
summary: We present foundation VLN model via developing an automated pipeline for large-scale navigation data generation, resulting in the GN-Matrix dataset and a high-fidelity simulation platform that supports interactive roaming and collision-aware navigation.
tags: []

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://telehuman-gn0.github.io/'
url_slides: ''
url_source: ''
url_video: ''
url_wechat: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Chenjia Bai'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
