---
layout: post
title: Robust Strategy Discovery
description: Used RL to discover clever strategies before teaching them to people
---

The goal in this project was to discover strategies for real-world problems and then teach them to people. Since a human's perception of the world is inaccurate due to inherent cognitive biases, it would be naive to assume that the decision-problem is exactly as described by them. What should we do then? Incorporate our knowledge about these biases in our RL algorithms!

To that end, I ran experiments to capture potentially erroneous accounts, mathematically modeled the cognitive biases, and employed Bayesian Inference to obtain the posterior distribution of the true environment structure. I then utilized this posterior to better the strategy-discovery methods. Teaching these discovered strategies improved people's perfomance!

This project formed my undergraduate thesis under Dr. Falk Lieder at Max Planck Institute for Intelligent Systems, Tuebingen, Germany. More on the project [homepage](https://re.is.mpg.de/research_projects/robust-strategy-discovery). 