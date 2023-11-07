---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing
sections:
  - block: about.avatar
    content:
      username: admin
      text: |-
        Hi, there! I'm **Yizhong Shao**, Undergraduate in UWaterloo/.
        {style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}

  - block: features
    content:
      title: Skills
      items:
        - name: Programming
          description: Python, C++ (LinkedIn certificated), MATLAB (LinkedIn certificated), SQL (LinkedIn certificated)
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: ML (LinkedIn certificated), Linear Programming, GIS data analysis (QGIS)
          icon: chart-line
          icon_pack: fas
        - name: Electrical Engineering
          description: Signals and systems, circuits, semi-conductors, grids, control theories, simulation
          icon: camera-retro
          icon_pack: fas
 
    design:
      background:
        color: grey
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: space.jpg
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
      css_class: d-flex fullscreen align-items-center
---
