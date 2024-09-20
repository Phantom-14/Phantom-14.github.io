---
title: Trajectory Planning with Optimization Algorithm
summary: This project aims to solve the problem of multi-agent path planning in complex environment using optimization algorithm.
tags:
- Trajectory Planning
date: "2024-05-28T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Safe sets and trajectories generated based on our baseline method and new method. 
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

In terms of optimization algorithm, we propose that LDDGWO improves GWO by combining LDD and DEWA to produce solutions with flexible positional updates and reduce the likelihood of solutions falling into local optima. 

Moreover, to address the issue of local optimum and premature convergence, RSCDWOA is proposed based on the whale optimization algorithm, combining the chaotic initialization, the reverse search and the differential evolution methods. It is theoretically proved that this algorithm is globally convergent in probability. When applied to path planning problems, the proposed optimization algorithm can effectively find a globally optimal and smoother path. Through simulation experiments with multi-UAVs, it is demonstrated that the proposed algorithm has better performance than the state-of-the-art methods in environment with both static and dynamic obstacles, reflecting the global convergence and robustness of the proposed algorithm. 

In terms of trajectory planning, we use an artificial potential field to construct planning scenarios, which provides a platform for the visualisation of guaranteed convergence in probability of RSCDWOA. In addition, the optimal strategy of the Stackelberg-Nash game is determined to address cooperative trajectory planning for multiple UAVs in desired formation configurations.