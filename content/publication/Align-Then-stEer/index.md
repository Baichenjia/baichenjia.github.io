---
title: "Align-Then-stEer: Adapting the Vision-Language Action Models through Unified Latent Guidance"
authors:
- Yang Zhang
- Chenwei Wang
- Ouyang Lu
- Yuan Zhao
- Yunfei Ge
- Zhenglong Sun
- Xiu Li
- Chi Zhang
- Chenjia Bai*
- Xuelong Li*

author_notes:
date: "2023-09-27T00:00:00Z"
doi: ""
draft: false

weight: 60

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-27T00:00:00Z"

# Publication type.
publication_types: ["under-review"]

# Publication name and optional abbreviated publication name.
publication: "under review"
publication_short: ""

abstract: Vision-Language Action Models (VLAMs) demonstrate remarkable capabilities in mapping language instructions to robot actions through vision perception. However, their limited ability to adapt to novel environments poses a significant challenge to real-world deployment. Existing methods tackle this by either fine-tuning the entire model or pre-training on large-scale embodied datasets, which can be computationally intensive or prone to catastrophic forgetting. To address this, we propose Align-Then-stEer (ATE), a framework that adapts VLAMs to novel environments through unified latent guidance. Specifically, ATE incorporates an environment-specific adapter to guide the latent representation of the original model. This adapter is trained via contrastive learning on a small amount of domain data, enabling efficient adaptation while preserving the model's original capabilities. We validate ATE on both simulation and real-world benchmarks, demonstrating its effectiveness in adapting VLAMs to novel environments with limited data and computational resources. Moreover, we show that ATE can handle significant domain shifts without compromising performance on the original domain.

# Summary. An optional shortened abstract.
summary: We propose Align-Then-stEer (ATE), a framework that adapts VLAMs to novel environments through unified latent guidance.

tags: []
featured: true

url_pdf: https://arxiv.org/abs/2509.02055
url_code: 'https://github.com/TeleHuman/Align-Then-Steer'
url_dataset: ''
url_poster: ''
url_project: 'https://align-then-steer.github.io/'
url_slides: ''
url_source: ''
url_video: ''
url_wechat: 'https://mp.weixin.qq.com/s/NChG3VeyMaKhJi61X_ON_A'

image:
  caption: 'Image credit: Chenjia Bai'
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
