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

* Contributed prerecordered talk at [Bernoulli-IMS One World Symposium 2020](https://www.worldsymposium2020.org/home) (August 2020).



{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
