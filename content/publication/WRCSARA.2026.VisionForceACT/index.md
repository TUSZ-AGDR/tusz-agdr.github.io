---
title: 'Vision-Force ACT: Multimodal Action Chunking for Robotic Bimanual Peg-in-Hole Assembly'

authors:
  - Mingqi Chen
  - Meijie Chen
  - Qiang Li
  - Zhong Ming
  - Chao Liu

# Conference date; replace with the official proceedings publication date when available.
date: '2026-08-21T00:00:00Z'
publishDate: '2026-08-21T00:00:00Z'

# Add the DOI and publisher link when the proceedings become available.
doi: ''
publication_types: ['paper-conference']

publication: In *2026 WRC Symposium on Advanced Robotics and Automation (WRC SARA)*
publication_short: In *WRC SARA 2026* (Best Paper Award Finalist)

abstract: 'Robotic bimanual peg-in-hole assembly requires accurate geometric alignment and compliant manipulation. Vision-based imitation learning is widely used in such kind of bimanual manipulation, which can efficiently locate and approach the target. However, visual observations could be ambiguous when the peg, hole or contact surface is occluded by the manipulators. This paper presents Vision-Force ACT, a multimodal extension of Action Chunking with Transformers (ACT) that incorporates bilateral wrist force/torque observations into both the conditional latent inference and the policy representation. The proposed method successfully outputs temporally coherent bimanual action chunks from synchronized images, joints state, and wrist F/T signals. A Mujoco-based simulated bimanual assembly platform equipped with 6-axis force/torque (F/T) sensor at both wrists is used in the experiment, and the proposed method is compared with the vision-only ACT baseline under identical training settings. The results show that Vision-Force ACT improves the task success rate from 40% to 68% with 50 demonstrations and from 60% to 78% with 200 demonstrations. The recorded F/T curves are also smoother than those of the vision-only policy and show closer agreement with the force demonstrations. These preliminary results support force sensing as an effective complement to visual observations for contact-rich bimanual imitation learning, while also motivating broader multi-task and real-robot validation.'

tags:
  - Bimanual Manipulation
  - Peg-in-Hole Assembly
  - Imitation Learning
  - Force Sensing
  - Best Paper Award Finalist

featured: true

url_pdf: '/publication/wrcsara.2026.visionforceact/index.pdf'

projects: []
slides: ''
---

{{% callout note %}}
Best Paper Award Finalist at **WRC SARA 2026**.
{{% /callout %}}
