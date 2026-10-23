---
title: "Graph-Reweighted Behavior Cloning with Human Interventions for Precise Robotic Manipulation"
authors:
  - Xiaoman Li
  - Zhiqiang Yang
  - Jiayu Hu
  - Jipeng Kong
  - Yang Zhang
  - Jingwei Zhang
  - Fangzheng Yan
  - Chunhua Shen*
  - Chenjia Bai*
author_notes:
date: "2026-10-14T00:00:00Z"
doi: ""
draft: false

weight: 107
publishDate: "2026-10-14T00:00:00Z"

publication_types: ["conference"]
publication: "In *Annual Conference on Robot Learning (**CoRL**)*, 2026"
publication_short: ""

abstract: "Graph-Reweighted Behavior Cloning (GR-BC) post-trains vision-language-action models using demonstrations and robot rollouts of mixed quality, including human interventions and failed episodes. A task-conditioned reachability graph connects the collected experience, and reverse search estimates the remaining steps to success. Action chunks receive training weights based on how much they reduce this distance, retaining useful recovery segments while suppressing regressions even within successful trajectories. New rollouts extend the graph for subsequent offline training rounds, without learned reward models or action-conditioned critics. Experiments across four precise manipulation tasks and three VLA backbones show improved performance over supervised fine-tuning, reaching 91% success after iterative training."
summary: GR-BC uses graph-derived task progress to reweight action chunks, learning precise manipulation from demonstrations, failed rollouts, and human interventions.

tags: []
featured: true
thumbnail: thumbnail.png

url_pdf: "https://arxiv.org/abs/2610.20504"
url_code: "https://github.com/Gamma-Robot/GR-BC"
url_dataset: ""
url_poster: ""
url_project: "https://gr-bc.github.io/"
url_slides: ""
url_source: ""
url_video: ""
url_wechat: ""
links:
  - name: OpenReview
    url: "https://openreview.net/forum?id=bsjuF5klA3"

image:
  caption: "Image credit: GR-BC authors. Thumbnail cropped from real-robot experiments."
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
