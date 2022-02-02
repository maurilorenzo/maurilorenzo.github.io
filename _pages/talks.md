---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% include base_path %}

**Invited talks**

* [Current developments in MCMC methods](https://www.impan.pl/en/activities/banach-center/conferences/21-mcmc), Institue of Mathematics, Warsaw, Poland (December 8-11, 2021).

* [Foundations of Objective Bayesian Methodology](https://www.birs.ca/events/2021/5-day-workshops/21w5107), BIRS, Oaxaca, México (November 28 - December 3, 2021).

* [EcoSta2021](http://www.cmstatistics.org/EcoSta2021/) 4th International Conference on Econometrics and Statistics, virtual (June 24-26, 2021).

**Contributed talks**

* [BAYSM 2021](https://events.stat.uconn.edu/BAYSM2021/) Bayesian Young Statisticians Meeting, virtual (September 1-3, 2021).

* [ISBA21](https://events.stat.uconn.edu/ISBA2021/) 2021 World Meeting of the International Society for Bayesian Analysis, virtual (June 28 - July 2, 2021).

* [ISBA@CIRM](https://sites.google.com/view/isba-at-cirm/junior-sessions) Junior session of ISBA@Cirm, Marseille, France (June 28 - July 2, 2021).

* [SIS2021](https://meetings3.sis-statistica.org/index.php/sis2021/) 50th Meeting of the Italian Statistical Society, virtual (June 21-25, 2021).

* [BAYSM:O](https://j-isba.github.io/baysmo.html) Bayesian Young Statisticians Meeting: Online, virtual (November 17-18, 2020).

* [Bernoulli-IMS One World Symposium 2020](https://www.worldsymposium2020.org/home), virtual (August 24-28, 2020).

**Poster sessions**

* [Bernoulli - IMS Young Researcher Meeting 2021](https://www.wc2020.org/sub03_04.php) (best poster award), virtual (July 17-18, 2021).

* [ISBA21](https://events.stat.uconn.edu/ISBA2021/) 2021 World Meeting of the International Society for Bayesian Analysis, virtual (June 28 - July 2, 2021).

* [BISP12](https://bisp12.imati.cnr.it/home_page.php) Bayesian Inference in Stochastic Processes, virtual (May 27-28, 2021).

* [BNP12](http://www.stats.ox.ac.uk/bnp12/) 12th International Conference on Bayesian Nonparametrics, Oxford, UK (June 24-28, 2019).



{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
