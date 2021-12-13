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

* Invited talk at [Current developments in MCMC methods](https://www.impan.pl/en/activities/banach-center/conferences/21-mcmc) (Warsaw, December 2021).

* Invited talk at [Foundations of Objective Bayesian Methodology](https://www.birs.ca/events/2021/5-day-workshops/21w5107) (December 2021).

* Contributed talk at [BAYSM 2021](https://events.stat.uconn.edu/BAYSM2021/) Bayesian Young Statisticians Meeting (September 2021).

* Poster presentation (with award) at [Bernoulli - IMS Young Researcher Meeting 2021](https://www.wc2020.org/sub03_04.php) (July 2021).

* Contributed talk and poster presentation at [ISBA21](https://events.stat.uconn.edu/ISBA2021/) 2021 World Meeting of the International Society for Bayesian Analysis (July 2021).

* Contributed talk at [ISBA@CIRM](https://sites.google.com/view/isba-at-cirm/junior-sessions) Junior session of ISBA@Cirm (Marseille, June 2021).

* Invited talk at [EcoSta2021](http://www.cmstatistics.org/EcoSta2021/) 4th International Conference on Econometrics and Statistics (June 2021).

* Contributed talk at [SIS2021](https://meetings3.sis-statistica.org/index.php/sis2021/) 50th Meeting of the Italian Statistical Society (June 2021).

* Virtual poster presentation at [BISP12](https://bisp12.imati.cnr.it/home_page.php) Bayesian Inference in Stochastic Processes (May 2021).

* Contributed talk at [BAYSM:O](https://j-isba.github.io/baysmo.html) Bayesian Young Statisticians Meeting: Online (November 2020).

* Contributed prerecorded talk at [Bernoulli-IMS One World Symposium 2020](https://www.worldsymposium2020.org/home) (August 2020).

* Poster session at [BNP12](http://www.stats.ox.ac.uk/bnp12/) 12th International Conference on Bayesian Nonparametrics (Oxford, UK, June 2019).



{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
