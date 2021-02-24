---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

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
