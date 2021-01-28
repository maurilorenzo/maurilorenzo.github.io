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

* Contributed prerecorded talk at [Bernoulli-IMS One World Symposium 2020](https://www.worldsymposium2020.org/home) (August 2020).

* Contributed talk at [BAYSM:O](https://j-isba.github.io/baysmo.html) Bayesian Young Statisticians Meeting: Online (November 2020).

* Poster session at [BNP12](http://www.stats.ox.ac.uk/bnp12/) 12th International Conference on Bayesian Nonparametrics (Oxford, UK, June 2019).



{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
