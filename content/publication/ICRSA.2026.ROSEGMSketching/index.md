---
title: 'ROS 2 and EGM-driven sketching pipeline for ABB collaborative robots'

authors:
  - Bartosz Piotr Lukawski
  - Daniel Gómez-Cubillo
  - Edwin Daniel Oña
  - Juan G. Victores
  - Carlos Balaguer
  - Alberto Jardón
  - Qiang Li

# Only the conference month is known; replace with the official proceedings date when available.
date: '2026-10-01T00:00:00Z'
publishDate: '2026-10-01T00:00:00Z'

# Add the DOI when the IEEE proceedings record is available.
doi: ''
publication_types: ['paper-conference']

publication: In *2026 International Conference on Robotic Systems and Applications (ICRSA)*
publication_short: In *ICRSA 2026*

abstract: 'This paper presents an open-source, end-to-end pipeline that automates robot sketching on an ABB CRB 15000-5 "GoFa" cobot from user-supplied images. The software integrates ROS 2 with ABB''s Externally Guided Motion (EGM) interface and features a graphical Python application for image acquisition, edge processing (via classical Canny edge detection with OpenCV, local AI models, or cloud APIs), vectorization, trajectory generation, and real-time execution preview. We provide an extensive empirical evaluation comparing Deep Reinforcement Learning (DQN, PPO, SAC) against a deterministic geometric approach. Results demonstrate that while discrete DQN achieves a high in-distribution similarity (Jaccard index of 0.601), it degrades significantly out-of-distribution. In contrast, the geometric method generalizes reliably across unseen targets and reaches a 149-times reduction in total sketch processing time (21.8 ms versus 3248 ms). The key contributions are an open-source ROS 2 driver interfacing EGM, a user-friendly GUI workflow, and a comparative benchmark of RL versus geometric trajectory generation for robot sketching.'

tags:
  - ROS 2
  - ABB Robots
  - Externally Guided Motion
  - Collaborative Robots
  - Robot Programming

featured: false

url_pdf: '/publication/icrsa.2026.rosegmsketching/paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ''
---

{{% callout note %}}
Accepted for **IEEE ICRSA 2026** (Huizhou, China, October 2026). The accepted manuscript is available as a PDF on this page; the DOI and official proceedings link will be added when they become available.
{{% /callout %}}
