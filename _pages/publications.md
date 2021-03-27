---
layout: archive
title: "Research"
excerpt: "Published and in progress"
header:
  overlay_image: https://jgnunol.github.io/images/harmonices.png
  caption: "From Kepler's Harmonices Mundi"
permalink: /publications/
redirect_from: 
  - /research/
  - /research.html
  - /portfolio/
  - /portfolio.html
author_profile: true
---
{% include base_path %}

* [Google Scholar](https://scholar.google.ca/citations?user=udjj4tsAAAAJ&hl=en).
* [RePEc/IDEAS](https://ideas.repec.org/e/pnu115.html).

## Publications
-------

{% for post in site.publications reversed %}
	{% if post.type == 'published' %}
		{% include archive-single.html %}
	{% endif%}
{% endfor %}


## Work in Progress
-------

{% for post in site.publications reversed %}
	{% if post.type == 'progress' %}
		{% include archive-single.html %}
	{% endif%}
{% endfor %}
