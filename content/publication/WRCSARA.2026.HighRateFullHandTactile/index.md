---
title: 'High-Rate Full-Hand Tactile Sensing for Sim-to-Real Recognition and Grasping'

authors:
  - Silin Qiu
  - Zhengyang Zhong
  - Yanyi Wang
  - Zhenyuan Zhang
  - Enrui Zhang
  - Jingke Lyu
  - Qiang Li

author_notes:
  - 'College of Engineering Physics, Shenzhen Technology University, Shenzhen 518118, Guangdong Province, China. These authors contributed equally to this work.'
  - 'School of Artificial Intelligence, Shenzhen Technology University, Shenzhen 518118, Guangdong Province, China. These authors contributed equally to this work.'
  - 'Future Technology School, Shenzhen Technology University, Shenzhen 518118, Guangdong Province, China.'
  - 'Future Technology School, Shenzhen Technology University, Shenzhen 518118, Guangdong Province, China.'
  - 'School of Artificial Intelligence, Shenzhen Technology University, Shenzhen 518118, Guangdong Province, China.'
  - 'School of Artificial Intelligence, Shenzhen Technology University, Shenzhen 518118, Guangdong Province, China.'
  - 'School of Artificial Intelligence, Shenzhen Technology University, Shenzhen 518118, Guangdong Province, China; Guangdong Provincial Engineering Technology Research Center for Edge Intelligence. Corresponding author.'

# The source PDF was created on 2026-07-22. Replace these dates with the official
# acceptance or proceedings date when WRC SARA 2026 publishes it.
date: '2026-07-22T00:00:00Z'
publishDate: '2026-07-22T00:00:00Z'

# Accepted for WRC SARA 2026; DOI and proceedings URL are not available yet.
doi: ''
publication_types: ['paper-conference']

publication: In *2026 WRC Symposium on Advanced Robotics and Automation (WRC SARA)*
publication_short: In *WRC SARA 2026*

abstract: 'Full-hand tactile sensing provides contact information that vision can hardly capture after a dexterous hand encloses an object. This is important for stable grasping and shape recognition under occlusion. This paper presents a full-hand tactile perception framework for sim-to-real dexterous grasping. The platform uses a four-finger dexterous hand with 16 degrees of freedom and an in-house, low-cost piezoresistive tactile sensing system densely integrated across the entire hand, providing stable high-rate tactile signals at 300 Hz. In simulation, MuJoCo is used to match the positions of different tactile sensing taxels. Ray-normal projection and local spacing correction align the tactile layout on the hand surface, while force-voltage calibration maps simulated tactile responses to the real voltage domain. A multi-patch tactile classifier is trained and evaluated with simulated and real data. The model achieves 73.33% accuracy on a real dataset with 150 object-grasp samples, and reaches 92.67% accuracy on the test set after fine-tuning with another 150 real samples. These results show that high-rate full-hand piezoresistive sensing, geometric taxel alignment, and calibrated tactile simulation can support practical grasp-based object shape recognition.'

tags:
  - Tactile Sensing
  - Dexterous Grasping
  - Sim-to-Real Transfer
  - Tactile Perception
  - MuJoCo

featured: true

# Add the official proceedings PDF or DOI URL once it is released.
url_pdf: ''
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
Accepted for presentation at the **2026 WRC Symposium on Advanced Robotics and Automation (WRC SARA 2026)**. The DOI and final proceedings link will be added when they become available.
{{% /callout %}}

This work develops a high-rate, full-hand piezoresistive tactile perception pipeline for sim-to-real object-shape recognition during dexterous grasping. The system combines a 16-DoF four-finger hand, 12 tactile patches with 620 physical taxels, 300 Hz tactile acquisition, taxel-aligned MuJoCo simulation, and force-voltage calibration.
