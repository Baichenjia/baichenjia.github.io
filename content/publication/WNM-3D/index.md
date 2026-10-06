---
title: "WNM-3D: A World Navigation Model with 3D Scene Conditioning for Closed-Loop VLN"
authors:
  - Yuehao Huang*
  - Yunzi Wu
  - Xiaotao Zhang
  - Xinhai Li
  - Jiankun Dong
  - Jiajun Lv
  - Chi Zhang
  - Chenjia Bai*
  - Yong Liu
  - Xuelong Li
author_notes: []
date: "2026-08-07T00:00:00Z"
doi: ""
draft: false

weight: 101
publishDate: "2026-08-07T00:00:00Z"

publication_types: ["preprint"]
publication: "arXiv preprint, 2026"
publication_short: ""

abstract: "WNM-3D is a generative world navigation model that jointly predicts future observations and navigation actions using persistent 3D scene context. A frozen geometry encoder processes monocular RGB history, and a trainable Scene-to-Token Adapter converts its features into a fixed-length prefix for a world-action Diffusion Transformer. Block-causal attention makes this geometric context available throughout future video-action generation. Training combines supervised learning from A*-generated demonstrations, DAgger-style adaptation on policy-visited states, and Counterfactual DanceGRPO refinement. Experiments on GN-Bench show stronger closed-loop navigation than VLM-based policies and a 2D-conditioned counterpart, with adaptation improving success and reinforcement learning further improving navigation success and path efficiency."
summary: WNM-3D conditions joint future-view and action generation on persistent 3D scene tokens, combining imitation learning, DAgger, and reinforcement learning for closed-loop visual-language navigation.

tags: []
featured: true
thumbnail: thumbnail.png

url_pdf: "https://arxiv.org/abs/2608.07267"
url_code: "https://github.com/TeleHuman/WNM-3D"
url_dataset: ""
url_poster: ""
url_project: "https://wnm-3d.github.io/"
url_slides: ""
url_source: ""
url_video: ""
url_wechat: ""

links:
  - name: Models
    url: "https://huggingface.co/TeleEmbodied/WNM-3D"

image:
  caption: "Image credit: WNM-3D authors"
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
