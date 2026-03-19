---
title: "Beyond Short-Horizon: VQ-Memory for Robust Long-Horizon Manipulation in Non-Markovian Simulation Benchmarks"
authors:
  - Honghui Wang
  - Zhi Jing
  - Jicong Ao
  - Shiji Song
  - Xuelong Li
  - Gao Huang
  - Chenjia Bai*
author_notes:
date: "2026-03-17T00:00:00Z"
doi: ""

draft: false

weight: 70
publishDate: "2026-03-17T00:00:00Z"

publication_types: ["preprint"]
publication: "arXiv preprint"
publication_short: ""

abstract: The high cost of collecting real-robot data has made robotic simulation a scalable platform for both evaluation and data generation. Yet most existing benchmarks concentrate on simple manipulation tasks such as pick-and-place, failing to capture the non-Markovian characteristics of real-world tasks and the complexity of articulated object interactions. To address this limitation, we present RuleSafe, a new articulated manipulation benchmark built upon a scalable LLM-aided simulation framework. RuleSafe features safes with diverse unlocking mechanisms, such as key locks, password locks, and logic locks, which require different multi-stage reasoning and manipulation strategies. These LLM-generated rules produce non-Markovian and long-horizon tasks that require temporal modeling and memory-based reasoning. We further propose VQ-Memory, a compact and structured temporal representation that uses vector-quantized variational autoencoders (VQ-VAEs) to encode past proprioceptive states into discrete latent tokens. This representation filters low-level noise while preserving high-level task-phase context, providing lightweight yet robust temporal cues that are compatible with existing Vision-Language-Action models (VLA). Extensive experiments on state-of-the-art VLA models and diffusion policies show that VQ-Memory consistently improves long-horizon planning, enhances generalization to unseen configurations, and enables more efficient manipulation with reduced computational cost.

summary: We introduce RuleSafe and VQ-Memory, a VQ-VAE temporal representation that boosts long-horizon manipulation in non-Markovian benchmarks.

tags: []
featured: true

url_pdf: https://arxiv.org/abs/2603.09513
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://vqmemory.github.io/'
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
