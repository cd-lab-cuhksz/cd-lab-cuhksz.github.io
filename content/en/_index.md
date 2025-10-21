---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        CD Lab
      image:
        filename: icon.png
      text: |
        <br>
        
        The **CD Lab** has been a center of excellence for Artificial Intelligence theory research since its founding in 2021.

  - block: markdown
    content:
      title: |
        About our work
      text: |
        We are currently working on the following research:
        
        - **Stable AI Control Theory**

        Developing stability-guaranteed data-driven control methods that systematically integrate learning and control, establishing a theoretical foundation for reliable AI operation in dynamic environments.
        - **Physical Model Development**
        
        Investigating how embodied agents can learn and internalize physical models from data, enabling robots to effectively understand and learn the physical characteristics of the real world.
        - **Embodied Control Systems**
        
        Researching whole-body dynamic stability control and adaptive generalization strategies, facilitated by physics-aware execution, to achieve more stable, practical, and physically consistent robotic behaviors.
        - **Reliable Learning Control**
        
        Constructing safety-guaranteed learning control algorithms to enhance adaptability and generalization in complex environments, promoting the reliable deployment of intelligent control systems in real-world applications.
  
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

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
