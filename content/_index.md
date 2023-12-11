---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
      image:
        filename: welcome.jpg
      text: |
        <br>

        Dexterous robotic manipulation is one of the top ten cutting-edge technologies in the field of intelligent robots. It is also an important breakthrough way to improve the level of intelligence society and improve peoples quality of life in the fields of industry, agriculture, medical rehabilitation and elderly care, logistics, and space/ocean. The research team combines fundamental research in robotics with industry needs to lay out four key research directions:

 
        - **Robot tactile perception and control**
        - **Multimodal and robotic skill learning**
        - **Human-computer interaction**
        - **Integration and application of intelligent robots in the Internet of Things**


        Through a combination of independent R&D and international cooperation, we carry out applciation driven fundamental research, prototype development, demonstration verification and industrialization work, The vision of our group is to build a world-class robotics laboratory and to develop the best mannipulating robots.
        
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---