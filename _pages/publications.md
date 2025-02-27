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
**Robust Approximate Sampling via Stochastic Gradient Barker Dynamics.**
*International Conference on Artificial Intelligence and Statistics (AISTATS)*, Oral Presentation (2% of submissions) [[pdf](https://proceedings.mlr.press/v238/mauri24a/mauri24a.pdf)].


**Submitted**

* Mauri, L. and Dunson, D. B. (2024).
**Factor pre-training in Bayesian multivariate logistic models.**
*Under Revision* [[arxiv](https://arxiv.org/abs/2409.17441)].

* Mauri, L., Anceschi, N., and Dunson, D. B. (2025).
**Spectral decomposition-assisted multi-study factor analysis.**
*Submitted* [[arxiv](https://arxiv.org/abs/2502.14600)].

**Ongoing Projects**

* Mauri, L., Tokdar, S. T. and Wang, H. (a-z) (2025+).
**Bayesian Density Estimation via the Tree-Logistic Gaussian Process Prior.**
*Working Paper*.

* Mauri, L. and Dunson, D. B. (2025+),
**Generalized Bayesian Kernel Similarity for Supervised Dimensionality Reduction.**
*Working Paper*.

* Mauri, L. and Dunson, D. B. (2025+),
**An eigedecomposition approach to modeling multi-omics data.**
*Working Paper*.

* Mauri, L. and Dunson, D. B. (2025+),
**Empirical Bayes for pooled low-rank covariance estimation.**
*Working Paper*.







{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
