---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in progress

{% include base_path %}

{% for post in site.progress reversed %}
  {% include archive-single.html %}
{% endfor %}
