---
title: "Reinforcement Learning Respondent Driven Sampling"
authors:
- Justin Weltz
- Angela Sun
- Yichi Zhang
- Alexander Volfovsky
- Eric Laber
date: "'2025-01-01'"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-02T02:34:20.335090Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*submitted to the Journal of the American Statistical Association*"
#publication_short: ""

abstract: Respondent-driven sampling (RDS) is widely used to study hidden or hard-to-reach populations by incentivizing study participants to recruit their social connections. The success and efficiency of RDS can depend critically on the nature of the incentives, including their number, value, call to action, etc. Standard RDS uses an incentive structure that is set {\em a priori} and held fixed throughout the study. Thus, it does not make use of accumulating information on which incentives are effective and for whom. We propose a reinforcement learning (RL) based adaptive RDS study design in which the incentives are tailored over time to maximize cumulative utility during the study.  We show that these designs are more efficient, cost-effective, and can generate new insights into the social structure of hidden populations. In addition, we develop methods for valid post-study inference which are non-trivial due to the adaptive sampling induced by RL as well as the complex dependencies among subjects due to latent (unobserved) social network structure.  We provide asymptotic regret bounds and illustrate its finite sample behavior through a suite of simulation experiments.  

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Reinforcement learning
- Hard-to-reach populations

featured: true


url_pdf: https://www.arxiv.org/pdf/2501.01505
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---
