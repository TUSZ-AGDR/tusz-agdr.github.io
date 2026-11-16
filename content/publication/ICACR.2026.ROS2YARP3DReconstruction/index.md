---
title: 'Modular ROS 2 and YARP end-to-end pipeline for 3D scene reconstruction using manipulator arms'

authors:
  - Bartosz Piotr Lukawski
  - Irene Calvo-Corredera
  - José Ignacio Ros-Pérez
  - Celia Martín-Parra
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

publication: In *2026 International Conference on Automation, Control and Robotics (ICACR)*
publication_short: In *ICACR 2026*

abstract: 'We present an end-to-end pipeline for live 3D scene reconstruction, from raw point cloud acquisition to final mesh generation, ready for 3D printing. The hardware setup relies on a consumer-grade RGB-D camera (e.g., the Intel RealSense), an optional turntable controlled via a low-cost microcontroller (Arduino board), and a robotic arm (we used the ABB CRB 15000 "GoFa" collaborative robot). The underlying software architecture relies on fully open-source tools, with the OpenCV implementation of the KinectFusion algorithm at its backbone. This approach leverages the popular ROS 2 and YARP robotic middlewares, enabling a distributed network of reusable, modular components. We seek to provide a flexible framework that can easily be extended to a wider range of tools and robots. The system has been validated across three real scenarios; the 3D scanned meshes of three different objects (rubber duck, toy robot, human head) of varying sizes and features have been obtained, successfully generating 1:1 scale 3D-printed models. The source code of all developed components is openly available.'

tags:
  - 3D Scene Reconstruction
  - ROS 2
  - YARP
  - Manipulator Arms
  - Robot Perception

featured: false

url_pdf: '/publication/icacr.2026.ros2yarp3dreconstruction/paper.pdf'
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
Accepted for **IEEE ICACR 2026** (Nanjing, China, October 2026). The accepted manuscript is available as a PDF on this page; the DOI and official proceedings link will be added when they become available.
{{% /callout %}}
