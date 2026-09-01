---
title: "VISTA: Vision-Grounded and Physics-Validated Adaptation of UMI Data for VLA Training"
authors:
  - Siyuan Yang
  - Linzheng Guo
  - Ouyang Lu
  - Zhaxizhuoma
  - Daoran Zhang
  - Xinmiao Wang
  - Ting Xiao
  - Fangzheng Yan
  - Zhijun Chen
  - Yan Ding
  - Chao Yu*
  - Chenjia Bai*
  - Xuelong Li*
author_notes:
date: "2026-06-04T00:00:00Z"
doi: ""

draft: false

weight: 78
publishDate: "2026-06-04T00:00:00Z"

publication_types: ["preprint"]
publication: "arXiv preprint"
publication_short: ""

abstract: "Universal Manipulation Interface (UMI) enables scalable real-world robot data collection without hardware-specific teleoperation, yet leveraging UMI data to train large-scale Vision-Language-Action (VLA) models remains fundamentally challenging. We identify two critical mismatches: wrist-mounted fisheye views, with severe radial distortion and local gripper-centric perspectives, are out-of-distribution for pretrained VLMs; and human-collected trajectories frequently violate kinematic limits, incur collisions, or exceed controller bandwidth, teaching VLA policies physically infeasible actions. To address the challenges, we present VISTA, a framework that bridges this dual gap through three synergistic components. (i) UMI-VQA, the first large-scale VQA dataset tailored to wrist-mounted fisheye observations, aligns VLM representations to the distorted visual regime via auxiliary vision-language supervision. (ii) A systematic physical-validation pipeline performs a data-completeness pre-check and scores each valid trajectory for trajectory continuity, self-collision risk, and execution fidelity before it enters training. (iii) A two-stage co-training recipe jointly learns vision-language grounding on UMI-VQA and action prediction on validated trajectories. Our experiments empirically show that incorporating UMI-VQA consistently improves downstream policy performance, and that physical-validation scores are strongly predictive of deployment success. On diverse simulation and real-world manipulation tasks, VISTA significantly outperforms strong baselines including pi_0.5, LingBot-VLA, and Wall-X. We release the physical-validation pipeline, UMI-VQA, validated trajectory data, and the pre-trained model for the community."

summary: VISTA aligns UMI fisheye perception and physically validates trajectories to improve VLA training across simulation and real-world manipulation.

tags: []
featured: true

url_pdf: 'https://arxiv.org/abs/2606.04708'
url_code: 'https://github.com/TeleHuman/umi-vista'
url_dataset: ''
url_poster: ''
url_project: 'https://tele-umi-vista.github.io/'
url_slides: ''
url_source: ''
url_video: ''
url_wechat: ''

image:
  caption: 'Image credit: VISTA authors'
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
