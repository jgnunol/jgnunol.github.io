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

---
title: "Regulating Sugar-Sweetened Beverages:"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2009-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
This is a test.

[Download paper here](http://academicpages.github.io/files/paper1.pdf)

Recommended Test <i>Journal 1</i>. 1(1).


## Work in progress

{% include base_path %}

{% for post in site.progress reversed %}
  {% include archive-single.html %}
{% endfor %}
