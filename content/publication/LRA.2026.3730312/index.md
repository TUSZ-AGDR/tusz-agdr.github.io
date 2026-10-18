---
title: 'Toward Bimanual Dexterous Grasp of Partially Observable Objects With Data Synthesis and Diffusion-Based Generation Approach'

authors:
  - Haoliang Xu
  - Zexiang Guo
  - Lipeng Chen
  - Syed Muhammad Nashit Arshad
  - Fei Chen
  - Qiang Li

author_notes:
  - 'Shenzhen Technology University. These authors contributed equally to this work.'
  - 'Shenzhen Technology University. These authors contributed equally to this work.'
  - 'Shanghai Jiao Tong University.'
  - 'Shenzhen Technology University.'
  - 'The Chinese University of Hong Kong.'
  - 'Shenzhen Technology University.'

date: '2026-09-02T00:00:00Z'
publishDate: '2026-09-02T00:00:00Z'

doi: '10.1109/LRA.2026.3730312'

publication_types: ['article-journal']

publication: In *IEEE Robotics and Automation Letters*
publication_short: In *IEEE RA-L*

abstract: 'Data-driven bimanual dexterous grasping remains challenging due to the lack of large-scale physically valid datasets and the difficulty of generating feasible bimanual grasps from partial observations. We propose an efficient bimanual grasp synthesis pipeline that decouples bimanual grasp generation into single-hand grasp optimization and Cartesian pairing, followed by geometric filtering and physics-based validation. Using this pipeline, we construct BiDexGen-Dataset, a large-scale synthesized bimanual grasp dataset containing millions of physically valid bimanual grasps across 2,397 objects. To exploit the synthesized data for real-world deployment, we further introduce BiDexGen, a diffusion-based generative model that directly generates feasible bimanual grasp configurations from partial object point clouds. To improve grasp generation from real-world partial perception, we design a contact-aware sampling strategy for training data construction that collects simulated observation-grasp pairs by aligning partially visible object regions with corresponding feasible grasps, enabling BiDexGen to generate feasible bimanual grasps from partial observations. Experiments show that our synthesis pipeline outperforms prior bimanual grasp synthesis methods in simulation success rate and generation efficiency. Trained on BiDexGen-Dataset, BiDexGen achieves 68.47% success in simulation and 71.00% on a real dual-arm robotic system.'

tags:
  - Bimanual Grasping
  - Dexterous Manipulation
  - Diffusion Models
  - Data Synthesis
  - Partial Observation

featured: false

url_pdf: 'https://ieeexplore.ieee.org/document/11676042/'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

projects: []
slides: ''
---
