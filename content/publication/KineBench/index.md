---
title: "KineBench: Benchmarking Embodied World Models via IDM-Free Kinematic Grounding"
authors:
  - Zeyu Liu
  - Zhangzhe Zhu
  - Yang Zhang
  - Chenyou Fan
  - Chenjia Bai*
  - Xuelong Li
author_notes:
date: "2026-02-26T00:00:00Z"
doi: ""

draft: false

weight: 79
publishDate: "2026-02-26T00:00:00Z"

publication_types: ["conference"]
publication: In *European Conference on Computer Vision (**ECCV**)*, 2026
publication_short: ""

abstract: Evaluating the physical consistency of embodied world models (EWMs) is a critical open challenge. While closed-loop evaluation via simulator rollouts offers a more faithful assessment of physical plausibility than open-loop alternatives, existing frameworks almost exclusively rely on Inverse Dynamics Models (IDMs) for action extraction. Due to the intricate mapping from 2D pixel space to 3D kinematic space, the learned IDMs can be brittle to data outside their training distribution, resulting in unreliable action extraction from the generated videos with novel objects and scenarios. This creates an unavoidable attribution ambiguity between world model inaccuracies and extractor errors. To eliminate this ambiguity, we present KineBench, the first IDM-free closed-loop benchmark for EWMs, built upon an explicit kinematic grounding pipeline. Given a generated video, KineBench employs cascaded visual foundation models to directly extract 6D end-effector poses from individual frames, which are then executed in a physics simulator for closed-loop validation. This explicit grounding directly tests the physical feasibility rather than visual plausibility, while remaining sensitive to general physical hallucinations such as gripper vanishing or spatial inconsistency. Beyond execution-based task success assessment, KineBench introduces two 3D kinematic metrics, Spectral Arc Length (SPARC) and the Maruyama Manipulability Index, to evaluate trajectory smoothness and kinematic dexterity from a robot-centric perspective. We empirically demonstrate a strong correlation between these metrics and physical success rate, establishing them as reliable proxies for embodied generation quality. Built on 20 diverse manipulation tasks in ManiSkill3, KineBench evaluates EWMs across four progressive suites, including basic execution, task transfer, visual out-of-distribution generalization, and complexity-conditioned scaling. Extensive evaluation of frontier models reveals a non-linear scaling behavior in embodied video generation bounded by task complexity, offering rigorous empirical guidance for future data scaling strategies.

summary: KineBench introduces the first IDM-free closed-loop benchmark for embodied world models, using explicit 3D kinematic grounding and robot-centric metrics for physical validation.

tags: []
featured: true

url_pdf: 'https://openreview.net/pdf?id=J4q7U5tx8S'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_wechat: ''

image:
  caption: 'Image credit: KineBench authors'
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
