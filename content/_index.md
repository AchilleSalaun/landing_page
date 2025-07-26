---
# title: 'Landing Page'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em; margin-bottom: -150px;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Learn more about my work on Machine Learning, Interpretable AI, and Web Semantic.
          icon: custom/graph
          url: https://achillesalaun.github.io/engineering/
        - text: Step into my creative world by visiting my art portfolio.
          icon: custom/palette
          url: https://achillesalaun.github.io/art/
---
