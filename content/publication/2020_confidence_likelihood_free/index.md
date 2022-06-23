---
title: "Confidence Sets and Hypothesis Testing in a Likelihood-Free Inference Setting"
date: 2020-02-05T00:03:00
draft: false
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- Niccolò Dalmasso
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
publication: "Proceedings of Machine Learning Research (ICML Track)"
#publication_short = "In *ICMEW*"

# Abstract and optional shortened version.

# Featured image thumbnail (optional)
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
tags : ["Approximate Likelihood","Confidence Intervals","Machine Learning"]

# Links (optional).
#url_pdf = ""
url_preprint : "https://arxiv.org/pdf/2002.10399.pdf"
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

summary: Parameter estimation, statistical tests and confidence sets are the cornerstones of classical statistics that allow scientists to make inferences about the underlying process that generated the observed data. A key question is whether one can still construct hypothesis tests and confidence sets with proper coverage and high power in a so-called likelihood-free inference (LFI) setting; that is, a setting where the likelihood is not explicitly known but one can forward-simulate observable data according to a stochastic model. We present ACORE, a frequentist approach to LFI that first formulates the classical likelihood ratio test (LRT) as a parametrized classification problem, and then uses the equivalence of tests and confidence sets to build confidence regions for parameters of interest. We also present a goodness-of-fit procedure for checking whether the constructed tests and confidence regions are valid. 

# Does this page contain LaTeX math? (true/false)
math: true

# Does this page require source code highlighting? (true/false)
highlight: true
---
