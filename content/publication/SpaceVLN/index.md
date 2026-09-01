---
title: "SpaceVLN: A Zero-Shot Vision-and-Language Navigation Agent with Online Spatial Cognitive Memory and Reasoning"
authors:
  - Yucheng Deng
  - Pingrui Lai
  - Xinhai Li
  - Chenjia Bai
  - Xiaoheng Deng
  - Chengnuo Sun
  - Xuelong Li*
  - Hua Yang*
author_notes:
date: "2026-06-08T00:00:00Z"
doi: ""

draft: false

weight: 77
publishDate: "2026-06-08T00:00:00Z"

publication_types: ["preprint"]
publication: "arXiv preprint"
publication_short: ""

abstract: "Vision-and-Language Navigation in continuous environments requires agents to understand the spatial structure of previously unseen environments in order to follow language instructions. Although foundation models have opened a promising path toward zero-shot navigation without task-specific policy training, many navigators still rely on local visual cues and linear history-based reasoning, overlooking the spatial nature of navigation across explored regions, traversed paths, landmarks, and their spatial relations. In this paper, we propose SpaceVLN, a navigation agent built around Spatial Cognitive Memory and Task-Guided Spatial Reasoning. Specifically, SpaceVLN introduces an efficient stagewise closed-loop framework where planning and execution are organized around verifiable space--landmark stages. During navigation, the agent progressively abstracts explored regions into Spatial Waypoints and dynamically maintains subtask-grounded landmark evidence, forming a hierarchical Spatial Cognitive Memory for progress localization and spatial-relation understanding. Built on this memory, Spatial-CoT integrates task-progress reasoning with spatial perception, analysis, and prediction, enabling Task-Guided Spatial Reasoning for embodied navigation. The unified stage interface enables SpaceVLN to address both Vision-and-Language Navigation and Object-Goal Navigation under a unified zero-shot setting, without task-specific policy training. Across R2R-CE, RxR-CE, GN-Bench, and HM3D-OVON, SpaceVLN achieves state-of-the-art zero-shot performance, and real-robot deployment further validates its applicability. These results highlight Spatial Cognitive Memory and Task-Guided Spatial Reasoning as a practical foundation for stronger embodied navigation agents."

summary: SpaceVLN introduces online Spatial Cognitive Memory and Task-Guided Spatial Reasoning for unified zero-shot VLN and Object-Goal Navigation.

tags: []
featured: true

url_pdf: 'https://arxiv.org/abs/2606.08992'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://charles-donne.github.io/SpaceVLN/'
url_slides: ''
url_source: ''
url_video: ''
url_wechat: ''

image:
  caption: 'Image credit: SpaceVLN authors'
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
