---
title: 'A Collision-Aware Cable Grasping Method in Cluttered Environment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lei Zhang
  - Kaixin Bai
  - Qiang Li
  - Zhaopeng Chen
  - Jianwei Zhang


# Author notes (optional)
author_notes:
  - 'TAMS (Technical Aspects of Multimodal Systems), Department of Informatics, Universit at Hamburg
  Agile Robots AG'
  - 'TAMS (Technical Aspects of Multimodal Systems), Department of Informatics, Universit at Hamburg
  Agile Robots AG'
  - 'TAMS (Technical Aspects of Multimodal Systems), Department of Informatics, Universit at Hamburg
  Corresponding authors.'
  - 'Agile Robots AG
  Corresponding authors.'
  - 'TAMS (Technical Aspects of Multimodal Systems), Department of Informatics, Universit at Hamburg'

date: '2024-05-13T00:00:00Z'
doi: '10.1109/ICRA57147.2024.10610559'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE International Conference on Robotics and Automation*
publication_short: In *ICRA 2024*


abstract: We introduce a Cable Grasping-Convolutional Neural Network (CG-CNN) designed to facilitate robust cable grasping in cluttered environments. Utilizing physics simulations , we generate an extensive dataset that mimics the intricacies of cable grasping, factoring in potential collisions between cables and robotic grippers. We employ the Approximate Convex Decomposition technique to dissect the non-convex cable model, with grasp quality autonomously labeled based on simulated grasping attempts. The CG-CNN is refined using this simulated dataset and enhanced through domain randomization techniques. Subsequently, the trained model predicts grasp quality, guiding the optimal grasp pose to the robot's controller for execution. Grasping efficacy is assessed across both synthetic and real-world settings. Given our model's implicit collision sensitivity, we achieved commendable success rates of 92.3% for known cables and 88.4% for unknown cables, surpassing contemporary state-of-the-art approaches. Supplementary materials can be found at https://leizhang-public.github.io/cg-cnn/.

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
image:
  caption: 'Grasping-cables-from-cluttered-scenes-exploiting-the-grasping-samples-approach-The-grasp'
  focal_point: ''
  preview_only: false

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
