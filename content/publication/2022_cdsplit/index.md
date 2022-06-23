---
abstract: Conformal methods create prediction bands that control average coverage assuming solely i.i.d. data. Although the literature has mostly focused on prediction intervals, more general regions can often better represent uncertainty. For instance, a bimodal target is better represented by the union of two intervals. Such prediction regions are obtained by CD-split, which combines the split method and a data-driven partition of the feature space which scales to high dimensions. CD-split however contains many tuning parameters, and their role is not clear. In this paper, we provide new insights on CD-split by exploring its theoretical properties. In particular, we show that CD-split converges asymptotically to the oracle highest predictive density set and satisfies local and asymptotic conditional validity. We also present simulations that show how to tune CD-split. Finally, we introduce HPD-split, a variation of CD-split that requires less tuning, and show that it shares the same theoretical guarantees as CD-split. In a wide variety of our simulations, CD-split and HPD-split have better conditional coverage and yield smaller prediction regions than other methods.
authors:
- admin
- Gilson Shimizu
- Rafael B. Stern
date: "2022-05-01T00:00:00Z"
doi: ""
featured: true
image:
  caption: ''
  focal_point: ""
  preview_only: false
publication: In *Journal of Machine Learning Research*
publication_short: In *JMLR*
publication_types:
- "2"
publishDate: "2022-05-01T00:00:00Z"
project: 
slides: 
summary: Conformal methods create prediction bands that control average coverage assuming solely i.i.d. data. We introduce CD-split and HPD-split, which yield general prediction regions and converge to the optimal highest predictive density set.
tags: [Conformal prediction,Machine Learning]
title: 'CD-split and HPD-split: Efficient conformal regions in high dimensions'
url_code: "https://github.com/rizbicki/predictionBands"
url_dataset: ""
url_pdf: "https://jmlr.org/papers/volume23/20-797/20-797.pdf"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
