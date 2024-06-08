---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        AI+Math Lab @ Korea
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        We expand the frontier of artificial intelligence with mathematics via research, teaching, and outreaching for the human race.
      # primary_action:
      #   text: Get Started
      #   url: https://example.com
      #   icon: sparkles
      # secondary_action:
      #   text: Read the docs
      #   url: https://example.com
      # announcement:
      #   text: Announcing the release of version 1.
      #   link:
      #     text: Read more
      #     url: https://example.com
  
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
          filename: ASB_lobby_2022.png
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
        {{% cta cta_link="./people/" cta_text="Meet the AIMLers →" %}}
    design:
      columns: '1'
---