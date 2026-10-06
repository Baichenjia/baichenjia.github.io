---
title: "V-JEPA Policy: Building Effective World-Action Models on Predictive Visual Latents"
authors:
  - Yang Zhang
  - Jiangyuan Zhao
  - Chenyou Fan
  - Jiayu Hu
  - Xiu Yuan
  - Chenjia Bai
  - Xiu Li*
author_notes: []
date: "2026-09-29T00:00:00Z"
doi: ""
draft: false

weight: 103
publishDate: "2026-09-29T00:00:00Z"

publication_types: ["preprint"]
publication: "arXiv preprint, 2026"
publication_short: ""

abstract: "V-JEPA Policy investigates whether predictive visual representations can support effective world-action models without adapting a complete pretrained visual generator. A frozen V-JEPA 2.1 encoder supplies the visual latent space, while an instruction-conditioned future predictor and a flow-matching action expert are jointly trained from scratch. Future-informed predictor states condition action generation. With 0.9 billion total parameters and 0.6 billion trainable parameters, the model performs competitively on LIBERO, LIBERO-Plus, and RoboCasa-GR1. Comparisons under matched training budgets show advantages over other visual representations, particularly under distribution shifts. Predictor pretraining on DROID video-instruction pairs without action labels further improves downstream control and generalization."
summary: V-JEPA Policy builds a compact world-action model on frozen predictive visual latents, jointly learning future prediction and action generation while transferring knowledge from videos without action labels.

tags: []
featured: true
thumbnail: thumbnail.png

url_pdf: "https://arxiv.org/abs/2609.37250"
url_code: "https://github.com/breez3young/VJEPA-Policy"
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
url_wechat: ""

image:
  caption: "Image credit: V-JEPA Policy authors"
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
