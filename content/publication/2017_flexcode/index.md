---
title: "Converting High-Dimensional Regression to High-Dimensional Conditional Density Estimation"
date: 2017-11-05T00:03:00
draft: false
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- admin
- Ann B. Lee
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types : ["1"]

# Publication name and optional abbreviated version.
publication: "Electronic Journal of Statistics"
#publication_short = "In *ICMEW*"

# Abstract and optional shortened version.

# Featured image thumbnail (optional)
featured: true
image:
  caption: ''
  focal_point: ""
  preview_only: false
  
# Is this a selected publication? (true/false)
featured: true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
# projects = ["example-external-project"]
categories : ["paper"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags : ["Nonparametric Statistics","Conditional Density Estimation","High-Dimensional Inference"]

# Links (optional).
#url_pdf : ""
url_pdf :"https://projecteuclid.org/euclid.ejs/1499133755"
url_preprint : "https://arxiv.org/pdf/1704.08095.pdf"
url_code : "https://github.com/rizbicki/FlexCoDE"
#url_code = ""
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

summary: Here we propose a fully nonparametric approach to conditional density estimation that reformulates CDE as a non-parametric orthogonal series problem where the expansion coefficients are estimated by regression. By taking such an approach, one can efficiently estimate conditional densities and not just expectations in high dimensions by drawing upon the success in high-dimensional regression. We show applications to photometric galaxy data, Twitter data, and line-of-sight velocities in a galaxy cluster.

# Does this page contain LaTeX math? (true/false)
math: true

# Does this page require source code highlighting? (true/false)
highlight: true
---