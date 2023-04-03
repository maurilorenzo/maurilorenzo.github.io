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

* Ascolani, F., Lijoi, A., Rebaudo, G. and Zanella, G. (2022+)
**Clustering consistency with Dirichlet process mixtures.**
*Biometrika*, forthcoming ([pdf](https://arxiv.org/abs/2205.12924)).

* Ascolani, F., Lijoi, A. and Ruggiero, M. (2023)
**Smoothing distributions for conditional Fleming--Viot and Dawson--Watanabe diffusions.**
*Bernoulli*, 29(2): 1410-1434 ([pdf](https://arxiv.org/abs/2204.12738)).

* Ascolani, F., Lijoi, A. and Ruggiero, M. (2021)
**Predictive inference with Fleming-Viot driven dependent Dirichlet processes.**
*Bayesian Anal.*, 16(2): 371-395 ([pdf](https://projecteuclid.org/journals/bayesian-analysis/advance-publication/Predictive-inference-with-FlemingViot-driven-dependent-Dirichlet-processes/10.1214/20-BA1206.full)).

**Papers under reviews**

* Ascolani, F., Franzolini, B., Lijoi, A. and Prünster, I. (2023+)
**Nonparametric priors with full-range borrowing of information.**
*Under Review*.

**Ongoing Projects**

* Ascolani, F., Lijoi, A. and Prünster, I. (2023+)
**Trees of random probability measures and Bayesian nonparametric modelling.**
*Working Paper*.

* Ascolani, F. and Zanella, G. (2023+)
**Complexity of Gibbs samplers through Bayesian asymptotics.**
*Working paper*.


**Discussions and Conference Proceedings**

* Ascolani, F., Catalano, M., Prünster, I. (2022). 
Discussion of **Evaluating sensitivity to the stick-breaking prior in Bayesian nonparametrics** by Giordano, R., Liu, R., Jordan, M.
I., and Broderick, T. 
*Bayesian Analysis*, 1 (1), 1-34 ([pdf](https://projecteuclid.org/journals/bayesian-analysis/volume--1/issue--1/Evaluating-Sensitivity-to-the-Stick-Breaking-Prior-in-Bayesian-Nonparametrics/10.1214/22-BA1309.full)).

* Ascolani, F., Franzolini, B., Lijoi, A. and Prünster, I. (2021)
**On the dependence structure in Bayesian nonparametric priors.**
*Book of Short Papers of the Italian Statistical Society*, Pearson ([pdf](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Università/pearson-sis-book-2021-parte-2.pdf)).

* Ascolani, F., Lijoi, A. Ruggiero, M. and Prünster, I. (2021)
**A framework for filtering in hidden Markov models with normalized random measures.**
*Book of Short Papers of the Italian Statistical Society*, Pearson ([pdf](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Università/pearson-sis-book-2021-parte-1.pdf)).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
