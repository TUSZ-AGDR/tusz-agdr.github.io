---
title: 'Learning an Image-Based Visual Servoing Controller for Object Grasping'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shuaijun Wang
  - Lining Sun
  - Mantian Li
  - Pengfei Wang
  - Fusheng Zha
  - Wei Guo
  - Qiang li


# Author notes (optional)
author_notes:
  - 'State Key Laboratory of Robotics and System, Harbin Institute of Technology, Harbin 150080,China wukongwoong@gmail.com'
  - 'State Key Laboratory of Robotics and System, Harbin Institute of Technology, Harbin 150080,China lnsun@hit.edu.cn'
  - 'State Key Laboratory of Robotics and System, Harbin Institute of Technology, Harbin 150080,China lmt@hit.edu.cn'
  - 'State Key Laboratory of Robotics and System, Harbin Institute of Technology, Harbin 150080,China pfwang@hit.edu.cn'
  - 'State Key Laboratory of Robotics and System, Harbin Institute of Technology, Harbin 150080,China fushengzha@hit.edu.cn
  Corresponding author'
  - 'State Key Laboratory of Robotics and System, Harbin Institute of Technology, Harbin 150080,China wguo01@hit.edu.cn
  Corresponding author'
  - 'Neuroinformatics Group, Center for Cognitive Interaction Technology (CITEC), Bielefeld University, 33619 Bielefeld, Germany qli@techfak.uni-bielefeld.de'
 
date: '2023-12-130T00:00:00Z'
doi: '10.1142/S0219843623500330'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Humanoid Robotics*
publication_short: In *International Journal of Humanoid Robotics*


abstract: Adaptive and cooperative control of arms and fingers for natural object reaching and grasping, without explicit 3D geometric pose information, is observed in humans. In this study, an image-based visual servoing controller, inspired by human grasping behavior, is proposed for an arm-gripper system. A large-scale dataset is constructed using Pybullet simulation, comprising paired images and arm-gripper control signals mimicking expert grasping behavior. Leveraging this dataset, a network is directly trained to derive a control policy that maps images to cooperative grasp control. Subsequently, the learned synergy grasping policy from the network is directly applied to a real robot with the same configuration. Experimental results demonstrate the effectiveness of the algorithm. Videos can be found at https://www.bilibili.com/video/BV1tg4y1b7Qe/.

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
