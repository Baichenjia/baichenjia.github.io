---
title: "Steering Vision-Language-Action Models as Anti-Exploration: A Test-Time Scaling Approach"
authors:
- Siyuan Yang
- Yang Zhang
- Haoran He
- Ling Pan
- Xiu Li
- Chenjia Bai*
- Xuelong Li*

author_notes:
date: "2025-12-02T00:00:00Z"
doi: ""
draft: false

weight: 63

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-02T00:00:00Z"

# Publication type.
publication_types: ["journal"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2512.02834"
publication_short: ""

abstract: Vision-Language-Action (VLA) models, trained via flow-matching or diffusion objectives, excel at learning complex behaviors from large-scale, multi-modal datasets. However, VLAs incorporate diverse data modes in the pre-training stage, and the finetuning dataset often contains demonstration data collected in a kinematically suboptimal or undesirable way, resulting in redundant action modes that are irrelevant to the success action modes of the downstream task. We observe a critical inference-time fragility among various sampled noises after supervised finetuning of pre-trained VLAs, attributed to the distribution shift between the VLA policy and the policy induced by stable success modes of the downstream task dataset. We propose TACO, a test-time-scaling (TTS) framework that applies a lightweight pseudo-count estimator as a high-fidelity verifier of action chunks. The VLA models integrated with TACO can execute the actions with maximum pseudo-count from all sampled action chunks, thereby preventing distribution shifts while preserving the generalization ability of VLAs since the constraint is applied only during inference. Our method resembles the classical anti-exploration principle in offline reinforcement learning (RL), and being gradient-free, it incurs significant computational benefits compared to RL update, especially for flow or diffusion-based VLAs which are difficult to perform RL update due to denoising process. Extensive experiments across four simulation benchmarks (RoboTwin2.0, Robotwin, LIBERO, SimplerEnv) and a dual-arm platform demonstrate that our method significantly improves the inference stability and success rates in downstream-task adaptations.

summary: We propose TACO, a test-time-scaling framework for VLAs that improves inference stability and success rates by preventing distribution shifts at test time.

tags: []
featured: true

url_pdf: https://arxiv.org/abs/2512.02834
url_code: 'http://github.com/TeleHuman/TACO'
url_dataset: ''
url_poster: ''
url_project: 'https://vla-anti-exploration.github.io/'
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
