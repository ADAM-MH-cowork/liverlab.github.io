---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Lab of Translational
        Liver Research
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Samsung Advanced Institute of Health Sciences and Technology (SAIHST)<br>
        Samsung Medical Center<br>
        여러 간 질환 극복을 위한 중개연구를 수행합니다.
  
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
      title: 우리의 연구
      subtitle: ''
      text: |
        간 섬유화, 간암, 간 이식 후 면역 등
        간 질환 전반에 대한 연구를 수행합니다.(이게맞을지...)
    design:
      columns: '1'
      background:
        image: 
          filename: research_bg.jpg
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
      title: Latest Publications
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
