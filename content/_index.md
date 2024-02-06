---
# Leave the homepage title empty to use the site title
title:
date: 2024-02-06
type: landing

sections:
  - block: hero
    content:
      title: |
        Cryptanalysis Taskforce
      image:
        filename: welcome.jpg
      text: |
        
        Established in 2014, we are a group of cryptography researchers from Nanyang Technological University in Singapore. Our research focuses are symmetric-key cryptology and privacy-preserving technologies. We are physically hosted by the Division of Mathematical Sciences of the School of

        Established in 2014, we are a group of cryptography researchers from Nanyang Technological University in Singapore. Our research focuses are symmetric-key cryptology and privacy-preserving technologies. We are physically hosted by the [Division of Mathematical Sciences](https://www.ntu.edu.sg/spms/about-us/mathematics) of the [School of Physical and Mathematical Sciences](https://www.ntu.edu.sg/spms), have been part of [Temasek Laboratories @ NTU](https://www.ntu.edu.sg/temasek-labs) and [Coding and Cryptography Research Group](http://www1.spms.ntu.edu.sg/~ccrg/), and in collaboration with [Shanghai Jiao Tong University, China](https://www.sjtu.edu.cn/). 
  
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