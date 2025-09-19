---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <div style="font-size:1.3rem">
          The BOLT
          Research Group
        </div>
        
      image:
        filename: welcome.jpg
      text: |
        <br>
        
         <div style="font-size:0.7rem;">
          The BOLT Research Group (Blockchain, Optimized Network, Ledger, Trust) focuses on building secure, high-performance distributed systems. Our research spans cryptographic protocols, P2P networks, source integrity, and trust in distributed environments. The name BOLT also reflects our recent work on the Bitcoin Lightning Network, highlighting fast, scalable, and secure payment channels. By combining foundational networking technologies with blockchain-based trust mechanisms, we aim to advance both theoretical and practical solutions for secure distributed systems.
        </div>
    
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
