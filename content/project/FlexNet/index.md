---
title: FlexNet for Cooperative Herding
summary: This project performs a novel cooperative herding strategy with an open-formation configuration called "FlexNet" in pursuit-evasion games under limited field of view.
tags:
- Pursuit-Evasion Games
date: "2024-07-24T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: An overview of FlexNet with an open-formation and field of view configuration for cooperative capture in pursuit-evasion games. 
  focal_point: Smart

# links:
# - icon: 
#   icon_pack: 
#   name: 
#   url: 
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

We propose an open formation (FlexNet) of pursuers to achieve effective capture of adversarial evaders. We expand the evader’s locomotion after equipping each pursuer with a finite FOV. Inspired by the interaction dynamics between agents during the herding process, a new segmented interaction model is developed for the evader to describe the influence of the pursuers. As shown in the figure, the pursuers with limited FOV first seek the evader and generate the desired formation. By gradually adjusting the size of the FlexNet, the pursuers finally achieve cooperative herding of the evader. 