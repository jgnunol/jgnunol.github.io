---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

[comment]: <> To include rs use (<u><a href="/files/rs.pdf">Research Statement</a></u>)

***Publications***
-------

{% for post in site.research reversed %}	
	{% if post.type == 'publication' %}
		{% include archive-single.html %}
	{% endif%}
{% endfor %}

***Working Papers***
-------

{% for post in site.research reversed %}
	{% if post.type == 'working %}
		{% include archive-single.html %}
	{% endif%}
{% endfor %}

***Work in Progress***
-------

{% for post in site.research reversed %}
	{% if post.type == 'progress' %}
		{% include archive-single.html %}
	{% endif%}
{% endfor %}


