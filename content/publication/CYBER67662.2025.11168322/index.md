---
title: "WMTDet: A Wavelet-Enhanced Multi-Scale Transformer Model for Precise PCB Defect Detection"

authors:
  - Yunfei Yan
  - Qiang Li
  - Lixin Liang
  - Ye
  - Gu

author_notes:
  - 'Shenzhen Technology University, Shenzhen, Guangdong 518118, China'
  - 'College of Big Data and Internet, Shenzhen Technology University, Shenzhen, Guangdong 518118, China. Email: liqiang1@sztu.edu.cn'
  - 'Shenzhen Technology University, Shenzhen, Guangdong 518118, China'
  - 'Shenzhen Technology University, Shenzhen, Guangdong 518118, China'
  - 'Shenzhen Technology University, Shenzhen, Guangdong 518118, China'

date: "2025-07-01T00:00:00Z"

doi: "10.1109/CYBER67662.2025.11168322"

publishDate: "2025-07-01T00:00:00Z"

publication_types: ["paper-conference"]

publication: In *2025 IEEE 15th International Conference on CYBER Technology in Automation, Control, and Intelligent Systems (CYBER)*
publication_short: In *IEEE CYBER 2025*

abstract: "Printed Circuit Board (PCB) defect detection is critical for ensuring the reliability of electronic devices in automated manufacturing, yet remains challenging due to the inherent complexity of detecting small, densely arranged, and low-contrast defects under varying scales. To address these challenges, we propose a novel multi-scale hierarchical detection framework, Wavelet-Enhanced Multi-Head Transformer Detector (WMTDet), which integrates wavelet-based feature decomposition, adaptive multi-scale attention, and fine-grained feature fusion. First, the backbone employs Wavelet Transform Convolutions (WTConv), enabling efficient large-receptive-field feature extraction while reducing parameter redundancy through multi-level frequency decomposition. Second, we propose a Multi-Scale Context Aggregation (MCA) module that synergies dilated convolutional priors and transformer-based attention mechanisms, enhancing the models capability to capture long-range dependencies and multi-resolution contextual cues. Third, a P2-guided feature pyramid is incorporated to preserve high-resolution shallow features. In the feature fusion stage, channel-weighted feature concatenation is proposed to differentiate importance between multi-scale feature maps. Extensive experiments on the PKU-Market-PCB and DeepPCB datasets demonstrate the superiority of our approach, achieving state-of-the-art APso scores of 99.3% and 99.1 %, respectively. This work provides a robust solution for industrial PCB inspection, balancing precision, efficiency, and scalability."

tags: ["PCB Defect Detection", "Wavelet", "Transformer", "Multi-Scale"]

url_pdf: "https://ieeexplore.ieee.org/abstract/document/11168322"

---