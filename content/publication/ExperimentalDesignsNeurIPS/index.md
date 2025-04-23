---
title: 'Experimental Designs for Heteroskedastic Variance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Justin Weltz
- Tanner Fiez
- Alexander Volfovsky
- Eric Laber
- Blake Mason
- Houssam Nassif
- Lalit Jain

date: '2024-01-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-02T02:34:20.335090Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Advances in Neural Information Processing Systems, 36*
publication_short: In NeurIPS

abstract: Most linear experimental design problems assume homogeneous variance, even though heteroskedastic noise is present in many realistic settings. Let a learner have access to a finite set of measurement vectors that can be probed to receive linear responses with heteroskedastic noise. The heteroskedastic variances of these responses are functions of the measurement vectors and an unknown parameter. We propose, analyze and empirically evaluate a novel design for uniformly bounding estimation error of the variance parameters. We demonstrate the benefits of this method with two adaptive experimental design problems under heteroskedastic noise, fixed confidence transductive best-arm identification, and level-set identification; proving the first instance-dependent lower bounds in these settings. Lastly, we construct near-optimal algorithms and empirically demonstrate the large improvements in sample complexity gained from accounting for heteroskedastic variance in these designs.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Heteroskedastic Variance
  - Experimental Design
  - Best-Arm Identification

# Display this page in the Featured widget?
featured: true

url_pdf: https://proceedings.neurips.cc/paper_files/paper/2023/hash/d01db5cd2555ba11f75da0454d57b903-Abstract-Conference.html
url_code: uploads/Var_Supplementary_Material.zip
#url_poster: uploads/UAI_Conference_poster.pdf


image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false
---