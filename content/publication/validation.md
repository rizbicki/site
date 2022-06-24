---
title : "Validation of Approximate Likelihood and Emulator Models for Computationally Intensive Simulations"
date : 2020-01-05T00:03:00
draft : false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors : [N. Dalmasso, A. B. Lee, admin , T. Pospisil, I. Kim ,   C. Lin]
  
# Publication type.
# Legend:
# 0 : Uncategorized
# 1 : Conference paper
# 2 : Journal article
# 3 : Manuscript
# 4 : Report
# 5 : Book
# 6 : Book section
publication_types : ["1"]

# Publication name and optional abbreviated version.
publication : "Proceedings of Machine Learning Research (AISTATS Track)"
#publication_short : "In *ICMEW*"

# Abstract and optional shortened version.
abstract : "Complex phenomena in engineering and the sciences are often modeled with computationally intensive feed-forward simulations for which a tractable analytic likelihood does not exist. In these cases, it is sometimes necessary to estimate an approximate likelihood or fit a fast emulator model for efficient statistical inference; such surrogate models include Gaussian synthetic likelihoods and more recently neural density estimators such as autoregressive models and normalizing flows. To date, however, there is no consistent way of quantifying the quality of such a fit. Here we propose a statistical framework that can distinguish any arbitrary misspecified model from the target likelihood, and that in addition can identify with statistical confidence the regions of parameter as well as feature space where the fit is inadequate. Our validation method applies to settings where simulations are extremely costly and generated in batches or 'ensembles' at fixed locations in parameter space. At the heart of our approach is a two-sample test that quantifies the quality of the fit at fixed parameter values, and a global test that assesses goodness-of-fit across simulation parameters. While our general framework can incorporate any test statistic or distance metric, we specifically argue for a new two-sample test that can leverage any regression method to attain high power and provide diagnostics in complex data settings."
abstract_short : ""

# Featured image thumbnail (optional)
image_preview : ""

# Is this a selected publication? (true/false)
featured : false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects : ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects : []`.
# projects : ["example-external-project"]

# Tags (optional).
#   Set `tags : []` for no tags, or use the form `tags : ["A Tag", "Another Tag"]` for one or more tags.
tags : ["Emulators","Validation","Approximate Likelihood","ABC"]

# Links (optional).
url_pdf : "http://proceedings.mlr.press/v108/dalmasso20a.html"
url_preprint : "https://arxiv.org/pdf/1905.11505.pdf"
#url_code : ""
#url_dataset : "#"
#url_project : "#"
#url_slides : "#"
#url_video : "#"
#url_poster : "#"
#url_source : "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom : [{name : "Custom Link", url : "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math : true

# Does this page require source code highlighting? (true/false)
highlight : true

---