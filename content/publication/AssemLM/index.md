---
title: "AssemLM: Spatial Reasoning Multimodal Large Language Models for Robotic Assembly"
authors:
  - Zhi Jing
  - Jinbin Qiao
  - Ouyang Lu
  - Jicong Ao
  - Shuang Qiu
  - Yu-Gang Jiang
  - Chenjia Bai
author_notes:
date: "2026-04-10T00:00:00Z"
doi: ""

draft: false

weight: 74
publishDate: "2026-04-10T00:00:00Z"

publication_types: ["preprint"]
publication: "arXiv preprint"
publication_short: ""

abstract: Spatial reasoning is a fundamental capability for embodied intelligence, especially for fine-grained manipulation tasks such as robotic assembly. While recent vision-language models (VLMs) exhibit preliminary spatial awareness, they largely rely on coarse 2D perception and lack the ability to perform accurate reasoning over 3D geometry, which is crucial for precise assembly operations. To address this limitation, we propose AssemLM, a spatial multimodal large language model tailored for robotic assembly. AssemLM integrates assembly manuals, point clouds, and textual instructions to reason about and predict task-critical 6D assembly poses, enabling explicit geometric understanding throughout the assembly process. To effectively bridge raw 3D perception and high-level reasoning, we adopt a specialized point cloud encoder to capture fine-grained geometric and rotational features, which are then integrated into the multimodal language model to support accurate 3D spatial reasoning for assembly tasks. In addition, we construct AssemBench, a large-scale dataset and benchmark for assembly-oriented spatial reasoning, comprising over 900K multimodal samples with precise 6D pose annotations. AssemBench extends spatial reasoning evaluation beyond 2D and grounding tasks into full 3D geometric inference, filling a critical gap in existing embodied AI benchmarks. Extensive experiments demonstrate that AssemLM achieves state-of-the-art performance in 6D pose reasoning across diverse assembly scenarios. Furthermore, real-robot evaluations show that our model can support fine-grained and multi-step assembly execution in real-world settings, demonstrating its potential for robotic assembly applications.

summary: AssemLM introduces a spatial multimodal LLM and AssemBench to advance 3D reasoning and 6D pose prediction for robotic assembly.

tags: []
featured: true

url_pdf: https://arxiv.org/abs/2604.08983
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
