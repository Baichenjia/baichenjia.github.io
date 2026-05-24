---
title: "Re^2MoGen: Open-Vocabulary Motion Generation via LLM Reasoning and Physics-Aware Refinement"
authors:
  - Jiakun Zheng
  - Ting Xiao
  - Shiqin Cao
  - Xinran Li
  - Zhe Wang
  - Chenjia Bai*
author_notes:
date: "2026-04-20T00:00:00Z"
doi: ""

draft: false

weight: 72
publishDate: "2026-04-20T00:00:00Z"

publication_types: ["preprint"]
publication: "arXiv preprint"
publication_short: ""

abstract: Text-to-motion (T2M) generation aims to control the behavior of a target character via textual descriptions. Leveraging text-motion paired datasets, existing T2M models have achieved impressive performance in generating high-quality motions within the distribution of their training data. However, their performance deteriorates notably when the motion descriptions differ significantly from the training texts. To address this issue, we propose Re^2MoGen, a Reasoning and Refinement open-vocabulary Motion Generation framework that leverages enhanced Large Language Model (LLM) reasoning to generate an initial motion planning and then refine its physical plausibility via reinforcement learning (RL) post-training. Specifically, Re^2MoGen consists of three stages: We first employ Monte Carlo tree search to enhance the LLM's reasoning ability in generating reasonable keyframes of the motion based on text prompts, specifying only the root and several key joints' positions to ease the reasoning process. Then, we apply a human pose model as a prior to optimize the full-body poses based on the planned keyframes and use the resulting incomplete motion to supervise fine-tuning a pre-trained motion generator via a dynamic temporal matching objective, enabling spatiotemporal completion. Finally, we use post-training with physics-aware reward to refine motion quality to eliminate physical implausibility in LLM-planned motions. Extensive experiments demonstrate that our framework can generate semantically consistent and physically plausible motions and achieve state-of-the-art performance in open-vocabulary motion generation.

summary: Re^2MoGen combines LLM reasoning, keyframe-guided completion, and physics-aware RL refinement for open-vocabulary text-to-motion generation.

tags: []
featured: true

url_pdf: https://arxiv.org/abs/2604.17807
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
