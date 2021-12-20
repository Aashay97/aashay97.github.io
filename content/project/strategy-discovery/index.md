---
title: Robust Strategy Discovery
summary: Used RL to discover clever strategies before teaching them to people
tags:
- Reinforcement Learning
- Computational Cognitive Science
date: "2020-08-31T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: Photo by rawpixel on Unsplash
  placement: 1

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: https://github.com/RationalityEnhancement/MCRL/tree/master/robust_strategy_discovery/risky-choice
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
slides: ""
---

The goal of this project was to discover strategies for real-world problems and then teach them to people. Since a human’s perception of the world is inaccurate due to inherent cognitive biases, it would be naive to assume that their description of the decision problem is accurate. What should we do then? Incorporate our knowledge about these biases in our RL algorithms!

To that end, I ran experiments to capture potentially erroneous accounts, mathematically modeled the cognitive biases, and employed Bayesian Inference to obtain the posterior distribution of the actual environment structure. I then utilized this posterior to better the strategy-discovery methods. Teaching the resultant strategies to people significantly improved their performance!

This project formed my undergraduate thesis under Dr. Falk Lieder at Max Planck Institute for Intelligent Systems, Tuebingen, Germany. More on the project [homepage](https://re.is.mpg.de/research_projects/robust-strategy-discovery). 