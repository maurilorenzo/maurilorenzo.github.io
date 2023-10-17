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

* [ISBA2024](https://www.unive.it/web/en/2208/home), World Meeting of the International Society for Bayesian Analysis, Venezia, Italy (July 1-7, 2024).

* [Cladag 2023](https://www.statlab-unisa.it/cladag2023/) CLAssification and Data Analysis Group of the Italian Statistical Society, Salerno, Italy (September 11-13, 2023).

* [SEAS IN 2023](https://meetings3.sis-statistica.org/index.php/ancona/index/pages/view/program) Statistical LEArning Sustainability and Impact Evaluation, Ancona, Italy (June 21-23, 2023).

* Seminar of [All about that Bayes](https://sites.google.com/view/all-about-that-bayes/) series, INRIA, Grenoble, France (November 8, 2022).

* [24th International Conference on Computational Statistics](http://www.compstat2022.org//index.php), Bologna, Italy (August 23-26, 2022).

* [Third Italian Meeting on Probability and Mathematical Statistics](https://site.unibo.it/probstat/en), Bologna, Italy (June 13-16, 2022).

* [Current developments in MCMC methods](https://www.impan.pl/en/activities/banach-center/conferences/21-mcmc), Institue of Mathematics, Warsaw, Poland (December 8-11, 2021).

* [Foundations of Objective Bayesian Methodology](https://www.birs.ca/events/2021/5-day-workshops/21w5107), BIRS, Oaxaca, México (November 28 - December 3, 2021).

* [EcoSta2021](http://www.cmstatistics.org/EcoSta2021/) 4th International Conference on Econometrics and Statistics, virtual (June 24-26, 2021).

**Contributed talks**

* [JSM2023](https://ww2.amstat.org/meetings/jsm/2023/), Joint Statistical Meeting, Toronto, Canada (August 5-10, 2023)

* [Bayes Comp 2023](https://bayescomp2023.com/), 2023 Meeting of the computational section of the International Society for Bayesian Analysis, Levi, Finland (March 15-17, 2023).

* [ISBA22](https://isbawebmaster.github.io/ISBA2022/), 2022 World Meeting of the International Society for Bayesian Analysis, Montreal, Canada (June 26 - July 1, 2022).

* [BNP Network 2022](http://cyprusconferences.org/bnp2022/), 2022 Bayesian Nonparametrics Networking Workshop, University of Cyprus, Cyprus (April 25 - 29, 2022).

* [BAYSM 2021](https://events.stat.uconn.edu/BAYSM2021/) Bayesian Young Statisticians Meeting, virtual (September 1-3, 2021).

* [ISBA21](https://events.stat.uconn.edu/ISBA2021/) 2021 World Meeting of the International Society for Bayesian Analysis, virtual (June 28 - July 2, 2021).

* [ISBA@CIRM](https://sites.google.com/view/isba-at-cirm/junior-sessions) Junior session of ISBA@Cirm, Marseille, France (June 28 - July 2, 2021).

* [SIS2021](https://meetings3.sis-statistica.org/index.php/sis2021/) 50th Meeting of the Italian Statistical Society, virtual (June 21-25, 2021).

* [BAYSM:O](https://j-isba.github.io/baysmo.html) Bayesian Young Statisticians Meeting: Online, virtual (November 17-18, 2020).

* [Bernoulli-IMS One World Symposium 2020](https://www.worldsymposium2020.org/home), virtual (August 24-28, 2020).

**Poster sessions**

* [Approximation Methods in Bayesian Analysis](https://conferences.cirm-math.fr/2768.html), CIRM, Marseille, France (June 19-23, 2023).

* [EAC-ISBA22](https://www.eac-isba.org/eacisba2022), 2022 Eastern Chapter of ISBA (**best poster award**), virtual (July 8-9, 2022).

* [ISBA22](https://isbawebmaster.github.io/ISBA2022/), 2022 World Meeting of the International Society for Bayesian Analysis (**best poster award**), Montreal, Canada (June 26 - July 1, 2022).

* [Bernoulli - IMS Young Researcher Meeting 2021](https://www.wc2020.org/sub03_04.php) (**best poster award**), virtual (July 17-18, 2021).

* [ISBA21](https://events.stat.uconn.edu/ISBA2021/) 2021 World Meeting of the International Society for Bayesian Analysis, virtual (June 28 - July 2, 2021).

* [BISP12](https://bisp12.imati.cnr.it/home_page.php) Bayesian Inference in Stochastic Processes, virtual (May 27-28, 2021).

* [BNP12](http://www.stats.ox.ac.uk/bnp12/) 12th International Conference on Bayesian Nonparametrics, Oxford, UK (June 24-28, 2019).



{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
