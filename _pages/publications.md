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
*International Conference on Artificial Intelligence and Statistics (AISTATS)*, Oral Presentation (2% of submissions) [pdf](https://proceedings.mlr.press/v238/mauri24a/mauri24a.pdf).

**Preprints**

* Mauri, L. and Dunson, D., B. (2024+).
**Factor pre-training in Bayesian multivariate logistic models.**

**Ongoing Projects**

* Mauri, L. Tokdar, S. T. and Wang, H. (2024+). 
**Bayesian Density Estimation via the Tree-Logistic Gaussian Process Prior.**
*Working Paper*.

* Mauri, L. Anceschi, N., and Dunson, D., B. (2024+).
**Latent Factors Pre-Training for Fast and Accurate Inference in Multi-Study Scenarios.**
*Working Paper*.

* Mauri, L. and Dunson, D., B. (2024+),
**Generalized Bayesian Kernel Similarity for Supervised Dimensionality Reduction.**
*Working Paper*.





{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
