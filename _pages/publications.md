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

* Ascolani, F., Lijoi, A. and Ruggiero, M. (2021)
**Predictive inference with Fleming-Viot driven dependent Dirichlet processes**
*Bayesian Analysis*, in press.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
