---
title: 'Towards Robust Physical Human Robot Interaction by an Adaptive Admittance Controller'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Guanghui Liu
  - Qiang li
  - Lijin Fang
  - Hualiang Zhang





# Author notes (optional)
author_notes:
  - 'Faculty of Robot Science and Engineering, Northeastern University, Shenyang, China'
  - 'Neuroinformatics Group & CITEC, Bielefeld University, Bielefeld, Germany'
  - 'Faculty of Robot Science and Engineering, Northeastern University, Shenyang, China'
  - ' Shenyang Institute of Automation, Chinese Academy of Sciences, Shenyang, China'

date: '2023-09-03T00:00:00Z'
doi: '10.1007/s10846-023-01999-9'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-03T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Intelligent & Robotic Systems*
publication_short: In *Journal of Intelligent & Robotic Systems 109(3)*


abstract: The regular admittance controller cannot be easily transferred to the physical human-robot interaction scenario because of the dynamic stiffness of the human arm. The dynamic interaction of humans can cause high frequency and unsafe oscillation of the robot arm. Based on the adaptive control scheme, this paper presents an online sensory-based analytical approach to recognize and quantify the "stability index" named as a robust haptic observer. The observer performs the Fast Fourier Transform on the interaction force signal within a sliding window and quickly detects system oscillation through a simple mathematical transformation. Compared with the existing methods, it can calculate a normalized system stability index more accurately and faster. This quantified index is employed in a linearized adaptive law to tune the parameters of the admittance controller. Experimental validation of the proposed strategy is performed and compared with state-of-the-art work in a task of human-guided drawing. The results show that our proposed approach can effectively detect oscillation, and the drawing time is shortened by 15% with the same tracking accuracy. In addition, the energy consumption is 44.4% less on average.

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
