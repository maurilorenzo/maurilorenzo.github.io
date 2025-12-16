---
layout: archive
title: "Publications and Ongoing Works"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

**Publications**

* Mauri, L. and Zanella, G. (2024)
**Robust approximate sampling via stochastic gradient Barker dynamics.**
*International Conference on Artificial Intelligence and Statistics (AISTATS)*, Oral Presentation (2% of submissions) [[pdf](https://proceedings.mlr.press/v238/mauri24a/mauri24a.pdf)].

* Mauri, L. and Dunson, D. B. (2025+)
**Factor pre-training in Bayesian multivariate logistic models.**
*Biometrika*, asaf056 [[article](https://academic.oup.com/biomet/advance-article/doi/10.1093/biomet/asaf056/8209919)] [[arxiv](https://arxiv.org/abs/2409.17441)].


**Submitted**

* Mauri, L., Anceschi, N., and Dunson, D. B. (2025)
**Spectral decomposition-assisted multi-study factor analysis.**
*Under revision* [[arxiv](https://arxiv.org/abs/2502.14600)].

* Mauri, L. and Dunson, D. B. (2025+)
**Inference on covariance structure in high-dimensional multiview data.**
*Under revision* [[arxiv](https://arxiv.org/abs/2509.02772)].

**Ongoing Projects**

* Mauri, L.°, Stolf, F.°, Herring, A. H., Miller, C., and Dunson, D. B. (2025+)
**Pathway-based Bayesian factor model for gene expression data.**
*Working Paper*.

* Mauri, L. and Dunson, D. B. (2025+)
**EigenBayes: Bayesian infinite factor models via adaptive spectral shrinkage.**
*Working Paper*.

* Mauri, L.  (2025+)
**Empirical Bayes subspace shrinkage for pooled covariance inference.**
*Working Paper*.

* Mauri, L., Ferrari, F., Johnson, M., Gleich, S., Skomsky, D. and Liaw, A. (2025+)
**Bayesian modeling of predictive stability under generalized Arrhenius non-linear kinetics.**
*Working Paper*.

* Mauri, L. and Dunson, D. B. (2025+)
**Generalized Bayesian kernel similarity for supervised dimensionality reduction.**
*Working Paper*.

* Mauri, L. and Dunson, D. B. (2025+)
**A Bayesian decision theoretic approach to sparse precision estimation.**
*Working Paper*.



° denotes equal contribution



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
