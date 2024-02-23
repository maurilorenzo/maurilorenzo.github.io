---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

**Journals**

* Ascolani, F. and Zanella, G. (2024)
**Dimension-free mixing times of Gibbs samplers for Bayesian hierarchical models.**
*Ann. Stat.*, forthcoming ([pdf](https://arxiv.org/abs/2304.06993)).

* Ascolani, F., Franzolini, B., Lijoi, A. and Prünster, I. (2023)
**Nonparametric priors with full-range borrowing of information.**
*Biometrika*, forthcoming ([pdf](https://arxiv.org/abs/2310.00617)).

* Ascolani, F., Lijoi, A., Rebaudo, G. and Zanella, G. (2023)
**Clustering consistency with Dirichlet process mixtures.**
*Biometrika*, 110(2), 551-558 ([pdf](https://arxiv.org/abs/2205.12924)).

* Ascolani, F., Lijoi, A. and Ruggiero, M. (2023)
**Smoothing distributions for conditional Fleming--Viot and Dawson--Watanabe diffusions.**
*Bernoulli*, 29(2): 1410-1434 ([pdf](https://arxiv.org/abs/2204.12738)).

* Ascolani, F., Lijoi, A. and Ruggiero, M. (2021)
**Predictive inference with Fleming-Viot driven dependent Dirichlet processes.**
*Bayesian Anal.*, 16(2): 371-395 ([pdf](https://projecteuclid.org/journals/bayesian-analysis/advance-publication/Predictive-inference-with-FlemingViot-driven-dependent-Dirichlet-processes/10.1214/20-BA1206.full)).

**Ongoing Projects**

* Ascolani, F., Lijoi, A. and Prünster, I. (2024+)
**Trees of random probability measures and Bayesian nonparametric modelling.**
*Working Paper*.


**Discussions and Conference Proceedings**

* Ascolani, F., Lijoi, A., Prünster, I. (2023). 
Discussion of **Martingale Posterior Distribution** by Fong, E., Holmes, C and Walker, S. G. 
*J. R. Stat. Soc. Series B*, 85 (5), 1357-1391.

* Ascolani, F., Catalano, M., Prünster, I. (2022). 
Discussion of **Evaluating sensitivity to the stick-breaking prior in Bayesian nonparametrics** by Giordano, R., Liu, R., Jordan, M.
I., and Broderick, T. 
*Bayesian Anal.*, 1 (1), 1-34 ([pdf](https://projecteuclid.org/journals/bayesian-analysis/volume--1/issue--1/Evaluating-Sensitivity-to-the-Stick-Breaking-Prior-in-Bayesian-Nonparametrics/10.1214/22-BA1309.full)).


* Ascolani, F. and Ghidini, V. (2023)
**Posterior clustering for Dirichlet Process Mixtures of Gaussians with constant data.**
*Book of Short Papers CLADAG 2023*, Pearson ([pdf](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Universit%C3%A0/CLADAG-2023.pdf)).

* Ascolani, F. and Ghidini, V. (2023)
**Linear models with assumptions-free residuals: a Bayesian Nonparametric approach**
*Book of short papers SEAS IN 2023*, Pearson ([pdf](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Universit%C3%A0/bozza-book-compresso-new1.pdf)).

"Mixing Times of a Gibbs Sampler for Probit Hierarchical Models." International Conference on Bayesian Statistics in Action
* Ascolani, F. (2022)
**Mixing Times of a Gibbs Sampler for Probit Hierarchical Models.**
*International Conference on Bayesian Statistics in Action*, Springer ([pdf](https://link.springer.com/chapter/10.1007/978-3-031-42413-7_7)).

* Ascolani, F., Franzolini, B., Lijoi, A. and Prünster, I. (2021)
**On the dependence structure in Bayesian nonparametric priors.**
*Book of Short Papers of the Italian Statistical Society*, Pearson ([pdf](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Università/pearson-sis-book-2021-parte-2.pdf)).

* Ascolani, F., Lijoi, A. Ruggiero, M. and Prünster, I. (2021)
**A framework for filtering in hidden Markov models with normalized random measures.**
*Book of Short Papers of the Italian Statistical Society*, Pearson ([pdf](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Università/pearson-sis-book-2021-parte-1.pdf)).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
