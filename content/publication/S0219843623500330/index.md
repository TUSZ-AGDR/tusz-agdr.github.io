---
title: 'Lp-slam: language-perceptive RGB-D SLAM framework exploiting large language model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weiyi Zhang
  - Yushi Guo
  - Niu Liting
  - Peijun Li
  - Zeyu Wan
  - Fei Shao
  - Fasih Ud
  - Fasih Ud Din Farrukh
  - Debing Zhang
  - Chun Zhang
  - Qiang li
  - Jianwei Zhang




# Author notes (optional)
author_notes:
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'School of Integrated Circuits, Tsinghua University, Haidian, Beijing 100084, China'
  - 'Group TAMS, Informatics and Natural Sciences Department of Informatics, Faculty of Mathematics, University of Hamburg, Vogt-Kölln-Straße 30 D, 22527 Hamburg, Germany'
  - 'Group TAMS, Informatics and Natural Sciences Department of Informatics, Faculty of Mathematics, University of Hamburg, Vogt-Kölln-Straße 30 D, 22527 Hamburg, Germany'

date: '2024-04-30T00:00:00Z'
doi: '10.1007/s40747-024-01408-0'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Complex & Intelligent Systems*
publication_short: In *Complex & Intelligent Systems*


abstract: With the development of deep learning, a higher level of perception of the environment such as the semantic level can be achieved in the simultaneous localization and mapping (SLAM) domain. However, previous works did not achieve a natural-language level of perception. Therefore, LP-SLAM (Language-Perceptive RGB-D SLAM) is proposed that leverages large language models (LLMs). The texts in the scene can be detected by scene text recognition (STR) and mapped as landmarks with a task-driven selection. A text error correction chain (TECC) is designed with a similarity classification method, a two-stage memory strategy, and a text clustering method. The proposed architecture is designed to deal with the mis-detection and mis-recognition cases of STR and to provide accurate text information to the framework. The proposed framework takes input images and generates a 3D map with sparse point cloud and task-related texts. Finally, a natural user interface (NUI) is designed based on the constructed map and LLM, which gives position instructions based on users’ natural queries. The experimental results validated the proposed TECC design and the overall framework. We publish the virtual dataset with ground truth, as well as the source code for further research. https://github.com/GroupOfLPSLAM/LP_SLAM.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
