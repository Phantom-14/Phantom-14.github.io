---
title: Manoeuvrability Pursuit-Evasion Games for Robots
summary: This project aims at dealing with problems including escape strategy, local optima, and uncertainty for multi-robot high-dimensional data.
tags:
- Pursuit-Evasion Games
date: "2024-09-20T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: An overall overview of the framework, including the architecture of MERL-GP and the application of multi-robot pursuit-evasion games.
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

Recently, multi-agent reinforcement learning (MARL) has made great progress in pursuit-evasion scenarios. A number of MARL methods are proposed, but they have their own disadvantages. Although these methods can improve the cooperative ability of robots, these methods do not apply to environments with a large number of robots as they require the use of all the robots’ states or observations in constructing their critic networks. As the number of robots increases, these methods will become increasingly difficult to be trained.

A whole novel method, called manoeuvrability enhanced reinforcement learning via gaussian process (MERL-GP), is proposed to deal with problems including escape strategy, local optima, and uncertainty for multi-robot high-dimensional data. MERL-GP contains manoeuvrability action, composite reward mechanism, and gaussian process. Specifically, manoeuvrability action provides more escape strategies. Composite reward mechanism overcomes the sparse reward and local optima problems. Gaussian process approximation solves the Q-function and allows an accurate online update of the parameters of the posterior mean and covariance. (Check our [video](https://youtu.be/TtiwqIaVDPs))