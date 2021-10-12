---
title: "Decision-specific sequences of neural activity in balanced random networks driven by structured sensory input"
event: "INM Retreat 2016"
event_url: ""

location: Institute for Neuroscience and Medicine
address:
  street: "Forchungszentrum J&uuml;lich"
  city: ""
  region: ""
  postcode: ""
  country: Germany

summary: ""
abstract: "Perceptual decision-making is an intricate process implicating the coordinated activity of multiple brain areas. Recent experimental studies demonstrate the existence of a complex interplay between decision-related neural events and transient working memory processes, implemented by distributed circuits where specific sub-populations appear to be differentially involved in the evidence accumulation process and subsequent behavioral outcomes. This results in observable divergences in choice-specific neuronal dynamics, unfolding as reproducible trajectories throughout the network’s state-space and hinting at the dissipative nature of the underlying dynamical system, which executes cognitively relevant processing through transient trajectories. Despite this evidence, the majority of modeling studies addressing reward-modulated decision-making tend to simplify the formalization of environmental representations in the cortex as stable, attractor states corresponding to discrete environmental states. Even models involving transient-based computations often simplify sensory stimuli to a discrete set of inputs transduced as stochastic point processes. These simplifications potentially draw an incomplete picture of neural dynamics and therefore provide limited insights into the true nature of computation in neural circuits. To overcome this issue, we take one step towards realistic in silico experimental settings by using structured virtual environments to obtain rich sensory input to drive model neural systems using the ROS-MUSIC toolchain. It allows us to simulate robotic agents in virtual 3D environments performing a realistic perceptual decision task, which can be directly equated to experimental data. The robotic simulation generates realistic and structured sensory data which is encoded to spiking neural activity using a nonlinear encoding process. The encoded sensory data is then used as input to a balance recurrent neural circuit. In this study, we investigate the emergent dynamical features of neural activity when the agent is navigating a virtual T-maze. We observe decision-specific sequences of neural activity akin to experimental evidence, revealing possible processing strategies employed by the neural substrate. Furthermore, we investigate the role of different adaptation/plasticity mechanisms in shaping the system’s dynamics. In order to equate our results with those of other studies, we attempt to partition the network state-space into discrete activity clusters, which carry relevant information that could potentially be used to drive reinforcement learning algorithms."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2016-10-12T10:00:00Z"
date_end: "2016-10-12T10:15:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2018-05-05T00:00:00Z"

authors: 
  - admin
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ""
  focal_point: Right

links:
- icon: chalkboard
  icon_pack: fas
  name: Slides
  url: https://doi.org/10.6084/m9.figshare.11492640.v1
  
# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Enable math on this page?
math: true
---

