---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <span style="font-weight:800;color:#005baa">C</span><span style="font-size:0.8em">omputer</span><br>
        <span style="font-weight:800;color:#005baa">A</span><span style="font-size:0.8em">nd</span><br>
        <span style="font-weight:800;color:#005baa">M</span><span style="font-size:0.8em">achine</span><br>
        <span style="font-weight:800;color:#005baa">E</span><span style="font-size:0.8em">ngaged</span><br>
        <span style="font-weight:800;color:#005baa">L</span><span style="font-size:0.8em">ab</span>
      image:
        filename: canine/canine1.png
      text: |
        <br>
        
        The **Computer and Machine Engaged Lab** has been a center of excellence for Physical Artificial Intelligence research, teaching, and practice since its founding in 2020.
  

  - block: markdown
    id: imitation-learning
    content:
      title: "Imitation Learning"
      subtitle: ""
      text: |
        <div style="display: flex; justify-content: center; gap: 20px; margin: 2rem 0;">
          <div style="text-align: center;">
            <video width="100%" height="auto" controls autoplay muted loop preload="auto" style="max-width: 400px; border-radius: 8px;">
              <source src="videos/rby1_2.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
          </div>
          <div style="text-align: center;">
            <video width="100%" height="auto" controls autoplay muted loop preload="auto" style="max-width: 800px; border-radius: 8px;">
              <source src="videos/rby1_1.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
          </div>
        </div>

  - block: markdown
    id: perceptive-locomotion
    content:
      title: "Perceptive Locomotion"
      subtitle: ""
      text: |
        <div style="display: flex; justify-content: center; gap: 20px; margin: 2rem 0;">
          <div style="text-align: center;">
            <video width="100%" height="auto" controls autoplay muted loop preload="auto" style="max-width: 800px; border-radius: 8px;">
              <source src="videos/perceptive_locomotion_1.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
          </div>
        </div>

  - block: markdown
    id: reinforcement-learning
    content:
      title: "Reinforcement Learning"
      subtitle: ""
      text: |
        <div style="display: flex; justify-content: center; gap: 20px; margin: 2rem 0;">
          <div style="text-align: center;">
            <video width="100%" height="auto" controls autoplay muted loop preload="auto" style="max-width: 800px; border-radius: 8px;">
              <source src="videos/rl_walk_1.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
          </div>
        </div>

  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 2rem 0; max-width: 1200px; margin-left: auto; margin-right: auto;">
          <div style="text-align: center;">
            <img src="images/canine/canine1.png" alt="첫 번째 이미지" width="500" style="border-radius: 8px;">
          </div>
          <div style="text-align: center;">
            <img src="images/lab_images/image42.png" alt="두 번째 이미지" width="500" style="border-radius: 8px;">
          </div>
          <div style="text-align: center;">
            <img src="images/lab_images/image43.png" alt="세 번째 이미지" width="500" style="border-radius: 8px;">
          </div>
          <div style="text-align: center;">
            <img src="images/lab_images/image33.png" alt="네 번째 이미지" width="500" style="border-radius: 8px;">
  

  # 첫 번째 슬라이더
  - block: slider
    content:
      slides:
        - title: ""
          content: ""
          align: center
          background:
            image:
              filename: canine/canine2.jpg
              fit: contain
              filters:
                brightness: 1.0
            position: center
        - title: ""
          content: ""
          align: center
          background:
            image:
              filename: canine/canine3.png
              fit: contain
              filters:
                brightness: 1.0
            position: center
    design:
      is_fullscreen: false
      slide_height: '60vh'
      interval: 4000
      loop: true
      css_style: "max-width: 1440px; margin-inline: auto;"

  # - block: slider
  #   content:
  #     slides:
  #       - title: "AI & ML"
  #         content: "Reinforcement Learning"
  #         align: center
  #         background:
  #           image:
  #             filename: lab_images/image22.png
  #           position: center
  #       - title: "Research Highlights"
  #         content: "Latest Publications"
  #         align: center
  #         background:
  #           image:
  #             filename: canine/canine2.jpg
  #             filters:
  #               brightness: 0.7
  #           position: center
  #         link:
  #           text: "See Publications"
  #           url: "/publication/"
  #   design:
  #     is_fullscreen: false
  #     slide_height: '60vh'
  #     interval: 4000
  #     loop: true
  #     css_style: "max-width: 100%; margin: 0;"

  # - block: slider
  #   content:
  #     slides:
  #       - title: "Welcome to the Lab"
  #         content: "3D Vision · Robotics · AI"
  #         align: center
  #         background:
  #           image:
  #             # 이미지 파일은 assets/media/ 에 두고 파일명만 적습니다.
  #             filename: canine/canine2.jpg
  #             # 필요 시 밝기/포지션 조절
  #             filters:
  #               brightness: 0.7
  #           position: center
  #       - title: "Research Highlights"
  #         content: "Locomotion / Perception / Reinforcement Learning"
  #         align: center
  #         background:
  #           image:
  #             filename: canine/canine3.png
  #             filters:
  #               brightness: 0.6
  #           position: right
  #         link:
  #           text: "See Publications"
  #           url: "/publication/"
  #       - title: ""
  #         align: center
  #         background:
  #           image:
  #             filename: lab_images/image22.png
  #           position: center
  #   design:
  #     is_fullscreen: false
  #     slide_height: '80vh'
  #     # slide_width: '100vh'
  #     interval: 5000
  #     loop: true
  #     css_style: "max-width: 1440px; margin-inline: auto;"
    
      
  - block: markdown
    id: section-1
    content:
      title: Section 1
      subtitle: A subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
  
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
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
