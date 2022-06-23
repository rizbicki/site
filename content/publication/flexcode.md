+++
title = "Converting High-Dimensional Regression to High-Dimensional Conditional Density Estimation"
date = 2017-11-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Izbicki, R.", "Lee, A.B."]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Electronic Journal of Statistics"
#publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "There is a growing demand for nonparametric conditional density estimators (CDEs) in fields such as astronomy and economics. In astronomy, for example, one can dramatically improve estimates of the parameters that dictate the evolution of the Universe by working with full conditional densities instead of regression (i.e., conditional mean) estimates. More generally, standard regression falls short in any prediction problem where the distribution of the response is more complex with multi-modality, asymmetry or heteroscedastic noise. Nevertheless, much of the work on high-dimensional inference concerns regression and classification only, whereas research on density estimation has lagged behind. Here we propose FlexCode, a fully nonparametric approach to conditional density estimation that reformulates CDE as a non-parametric orthogonal series problem where the expansion coefficients are estimated by regression. By taking such an approach, one can efficiently estimate conditional densities and not just expectations in high dimensions by drawing upon the success in high-dimensional regression. Depending on the choice of regression procedure, our method can adapt to a variety of challenging high-dimensional settings with different structures in the data (e.g., a large number of irrelevant components and nonlinear manifold structure) as well as different data types (e.g., functional data, mixed data types and sample sets). We study the theoretical and empirical performance of our proposed method, and we compare our approach with traditional conditional density estimators on simulated as well as real-world data, such as photometric galaxy data, Twitter data, and line-of-sight velocities in a galaxy cluster."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
# projects = ["example-external-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Nonparametric Statistics","Conditional Density Estimation","High-Dimensional Inference"]
categories = ["paper"]

# Links (optional).
url_pdf = "https://projecteuclid.org/euclid.ejs/1499133755"
url_preprint = "https://arxiv.org/pdf/1704.08095.pdf"
url_code = "https://github.com/rizbicki/FlexCoDE"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
# image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

