---
title: 'Modeling human eye movements with neural networks in a maze-solving task'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Nicholas Watters
  - Yingting (Sandy) Wang
  - Hansem Sohn
  - Mehrdad Jazayeri

# Author notes (optional)
author_notes:

date: '2022-12-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of Machine Learning Research*, 210 (NeurIPS 2022 Gaze Meets ML Workshop), 98-112 
publication_short:

# Summary. An optional shortened abstract.
summary: What computational objectives guide where we look? By developing a new neural network framework, GazeRNNs, to model eye movements during maze solving, we found evidence that mental simulation is a potential driver of our eye movements.

abstract: From smoothly pursuing moving objects to rapidly shifting gazes during visual search, humans employ a wide variety of eye movement strategies in different contexts. While eye movements provide a rich window into mental processes, building generative models of eye movements is notoriously difficult, and to date the computational objectives guiding eye movements remain largely a mystery. In this work, we tackled these problems in the context of a canonical spatial planning task, maze-solving. We collected eye movement data from human subjects and built deep generative models of eye movements using a novel differentiable architecture for gaze fixations and gaze shifts. We found that human eye movements are best predicted by a model that is optimized not to perform the task as efficiently as possible but instead to run an internal simulation of an object traversing the maze. This not only provides a generative model of eye movements in this task but also suggests a computational theory for how humans solve the task, namely that humans use mental simulation.

tags:
  - Saccade
  - Recurrent Network
  - Maze
  - Psychophysics
  - Fovea
  - Mental Simulation

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/pdf/2212.10367

url_pdf: 'https://proceedings.mlr.press/v210/li23a/li23a.pdf'
url_code: 'https://github.com/jazlab/Maze_Task_2022'
url_dataset: ''
url_poster: 'https://jasonlicodes.github.io/publication/gmml2022/GMML_poster.pdf'
url_project: ''
url_slides: 'https://jasonlicodes.github.io/publication/gmml2022/GMML_presentation.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 'gazernn'

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
