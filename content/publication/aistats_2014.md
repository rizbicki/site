---
title : "High-Dimensional density ratio estimation with extensions to approximate likelihood computation"
date : 2014-12-01T00:00:00
draft : false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors : [admin, A. B. Lee ,C. M. Schafer]

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
publication : "Journal of Machine Learning Research (AISTATS Track)"
#publication_short : "In *ICMEW*"

# Abstract and optional shortened version.
abstract : "The ratio between two probability density functions is an important component of various tasks, including selection bias correction, novelty detection and classification. Recently, several estimators of this ratio have been proposed. Most of these methods fail if the sample space is high-dimensional, and hence require a dimension reduction step, the result of which can be a significant loss of information. Here we propose a simple-toimplement, fully nonparametric density ratio estimator that expands the ratio in terms of the eigenfunctions of a kernel-based operator; these functions reflect the underlying geometry of the data (e.g., submanifold structure), often leading to better estimates without an explicit dimension reduction step. We show how our general framework can be extended to address another important problem, the estimation of a likelihood function in situations where that function cannot be wellapproximated by an analytical form. One is often faced with this situation when performing statistical inference with data from the sciences, due the complexity of the data and of the processes that generated those data. We emphasize applications where using existing likelihood-free methods of inference would be challenging due to the high dimensionality of the sample space, but where our spectral series method yields a reasonable estimate of the likelihood function. We provide theoretical guarantees and illustrate the effectiveness of our proposed method with numerical experiments."
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
tags : ["Machine Learning","Conference","Nonparametric Statistics","Density Ratio","Likelihood Estimation","ABC"]

# Links (optional).
url_pdf : "http://proceedings.mlr.press/v33/izbicki14.pdf"
#url_preprint : ""
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
