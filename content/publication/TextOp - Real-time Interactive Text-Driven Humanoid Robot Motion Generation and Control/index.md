---
title: "TextOp: Real-time Interactive Text-Driven Humanoid Robot Motion Generation and Control"
authors:
- Weiji Xie
- Jiakun Zheng
- Jinrui Han
- Jiyuan Shi
- Weinan Zhang*
- Chenjia Bai*
- Xuelong Li
author_notes:
date: "2026-02-12T00:00:00Z"
doi: ""

weight: 65

# Schedule page publish date (NOT publication's date).
publishDate: "2026-02-12T00:00:00Z"

# Publication type.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: "Recent advances in humanoid whole-body motion tracking have enabled the execution of diverse and highly coordinated motions on real hardware. However, existing controllers are commonly driven either by predefined motion trajectories, which offer limited flexibility when user intent changes, or by continuous human teleoperation, which requires constant human involvement and limits autonomy. This work addresses the problem of how to drive a universal humanoid controller in a real-time and interactive manner. We present TextOp, a real-time text-driven humanoid motion generation and control framework that supports streaming language commands and on-the-fly instruction modification during execution. TextOp adopts a two-level architecture in which a high-level autoregressive motion diffusion model continuously generates short-horizon kinematic trajectories conditioned on the current text input, while a low-level motion tracking policy executes these trajectories on a physical humanoid robot. By bridging interactive motion generation with robust whole-body control, TextOp unlocks free-form intent expression and enables smooth transitions across multiple challenging behaviors such as dancing and jumping, within a single continuous motion execution. Extensive real-robot experiments and offline evaluations demonstrate instant responsiveness, smooth whole-body motion, and precise control. The project page and the open-source code are available at https://text-op.github.io/"

# Summary. An optional shortened abstract.
summary: "Real-time text-driven humanoid motion generation and control using a two-level diffusion-and-tracking architecture (TextOp)."

tags: ""
  
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2602.07439.pdf'
url_code: 'https://github.com/TeleHuman/Textop'
url_dataset: ''
url_poster: ''
url_project: 'https://text-op.github.io/'
url_slides: ''
url_source: 'https://arxiv.org/abs/2602.07439'
url_video: ''
url_wechat: 'https://mp.weixin.qq.com/s/BwWBi4TwJCoJ94LKcMf8eg'

# Featured image
image:
  caption: ''
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---

