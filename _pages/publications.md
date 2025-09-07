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

* Mauri, L. and Zanella, G. (2024).
**Robust approximate sampling via stochastic gradient Barker dynamics.**
*International Conference on Artificial Intelligence and Statistics (AISTATS)*, Oral Presentation (2% of submissions) [[pdf](https://proceedings.mlr.press/v238/mauri24a/mauri24a.pdf)].

* Mauri, L. and Dunson, D. B. (2025+).
**Factor pre-training in Bayesian multivariate logistic models.**
*Biometrika*, asaf056 [[arxiv](https://arxiv.org/abs/2409.17441)].


**Submitted**

* Mauri, L., Anceschi, N., and Dunson, D. B. (2025).
**Spectral decomposition-assisted multi-study factor analysis.**
*Submitted* [[arxiv](https://arxiv.org/abs/2502.14600)].

* Mauri, L. and Dunson, D. B. (2025+),
**Inference on covariance structure in high-dimensional multiview data.**
*Submitted* [[arxiv](https://arxiv.org/abs/2509.02772)].

**Ongoing Projects**

* Mauri, L. and Dunson, D. B. (2025+),
**Generalized Bayesian kernel similarity for supervised dimensionality reduction.**
*Working Paper*.

* Mauri, L. and Dunson, D. B. (2025+),
**Hierarchical subspace shrinkage for covariance estimation of high-dimensional grouped data.**
*Working Paper*.

* Mauri, L. and Dunson, D. B. (2025+),
**A Bayesian decision theoretic approach to sparse precision estimation.**
*Working Paper*.

* Mauri, L.°, Stolf, F.°, Herring, A. H., Miller, C., and Dunson, D. B. (2025+),
**Pathways-based Bayesian factor model for gene expression data.**
*Working Paper*.

° denotes equal contribution



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
