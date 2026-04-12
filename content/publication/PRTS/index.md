---
title: "PRTS: A Primitive Reasoning and Tasking System via Contrastive Representations"
authors:
  - Yang Zhang
  - Jiangyuan Zhao
  - Chenyou Fan
  - Fangzheng Yan
  - Tian Li
  - Xuaner Wu
  - Qizhen Weng
  - Xiu Li
  - Weinan Zhang
  - Chi Zhang
  - Chenjia Bai*
  - Xuelong Li*
author_notes:
date: "2026-01-01T00:00:00Z"
doi: ""

weight: 73

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]

# Publication name and optional abbreviated publication name.
publication: "Under Review. 2026"
publication_short: ""

abstract: "Vision-Language-Action (VLA) models have advanced robotic control through dual-system architectures that separate semantic planning from action generation. However, existing approaches predominantly frame policy learning as supervised action prediction, overlooking the fundamental nature of robot learning as a goal-reaching process that requires understanding temporal task progress. We present PRTS (Primitive Reasoning and Tasking System), a foundation model that reformulates VLA pretraining through the lens of Goal-Conditioned Reinforcement Learning. By treating language instructions as goals and employing contrastive representation learning, PRTS learns a unified embedding space where state-goal alignment explicitly encodes log-discounted state occupancy that measures the probability of reaching goal starting from the current observation, enabling quantitative assessment of physical feasibility beyond superficial semantic matching. This paradigm equips the high-level planning system with intrinsic value awareness to evaluate candidate sub-tasks and guide low-level control optimization, bridging the gap between abstract reasoning and goal-conditioned action. Pretrained on over 167.8 billion tokens of diverse robotic trajectories, PRTS achieves state-of-the-art performance across standard simulation benchmarks and a comprehensive real-world evaluation suite spanning complex long-horizon manipulation tasks, validating that goal-reaching representation learning significantly enhances robustness and success rates in embodied AI systems."

# Summary. An optional shortened abstract.
summary: We introduce PRTS, a New Generation of Reinforcement Learning-Native Robotic Vision-Language-Action(VLA) foundation model. 
tags: []

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: 'https://huggingface.co/datasets/TeleEmbodied/PRTS-PostTrain-Data'
url_poster: ''
url_project: 'https://rhodes-team-prts.github.io/'
url_slides: ''
url_source: ''
url_video: ''
url_wechat: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Chenjia Bai'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
