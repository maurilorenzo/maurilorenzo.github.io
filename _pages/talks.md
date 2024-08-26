---
layout: archive
title: "Talks and Poster Sessions"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% include base_path %}

**Invited talks**

*[AISTATS2024](http://aistats.org/aistats2024/), The 27th International Conference on Artificial Intelligence and Statistics, Valencia, Spain (May 1-4, 2024).
*Robust Approximate Sampling via Stochastic Gradient Barker Dynamics*.

**Poster Sessions**
* [ISBA2024](https://www.unive.it/web/en/2208/home), World Meeting of the International Society for Bayesian Analysis, Venezia, Italy (July 1-7, 2024).
*Fast Latent Factors Pre-estimation for High-Dimensional Binary Data*-


{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
