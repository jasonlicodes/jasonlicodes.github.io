---
title: "Creating spatially-detailed heterogeneous synthetic populations for agent-based microsimulation"
authors:
- Meng Zhou
- admin
- Rounaq Basu
- Joseph Ferreira
author_notes:
date: "2022-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computers, Environment and Urban Systems, 91*, 101717"
publication_short: ""

abstract: Agent-based models (ABMs) of urban systems have grown in popularity and complexity due to the widespread availability of high-performance computing resources and large data storage capabilities. Credible synthetic populations are crucial for the application of ABMs to understand urban phenomena. Although several (agent) population synthesis methods have been suggested over the years, the spatial dimension of synthetic populations has not received as much attention. This study addresses this myopic treatment of synthetic populations by creating two distinct components – agents and the built environment – that are integrated to form a ‘full’ spatially-detailed synthetic population. To generate agents, we used multiple Bayesian Networks (BN) to probabilistically draw pools from the microsample, followed by a Generalized Raking (GR) adjustment to match marginal controls. Using various measures, we demonstrate that our BN + GR framework outperforms more commonly used synthesis methods in both capturing the heterogeneity in the microsample and matching marginal controls. We also highlight the importance of accounting for heterogeneity by using separate type-specific models based on an explicitly defined household typology. For built environment synthesis, we generated various spatial entities such as buildings, housing units, establishments, and jobs at distinct spatial locations by fusing data from various spatial datasets. Their spatial distributions are found to effectively approximate the ‘real’ built environment in our study area. Our proposed framework can be used to generate a ‘full’ synthetic population for use in ABMs with more spatio-demographic heterogeneity than can otherwise be estimated using traditional methods.

# Summary. An optional shortened abstract.
summary: 

tags:
- Synthetic population 
- Built environment 
- Agent-based microsimulation 
- Bayesian Network 
- Land use-transport interaction (LUTI) model

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://jasonlicodes.github.io/publication/zhou2022/zhou2022.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://doi.org/10.1016/j.compenvurbsys.2021.101717'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
  focal_point: ""
  preview_only:

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

