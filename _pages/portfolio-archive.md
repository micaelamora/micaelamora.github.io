---
title: Portfolio
layout: single
permalink: /portfolio/
classes: wide
---
## Digital Fabrication Projects
My digital fabrication projects:

{% assign fab = site.portfolio | where: "category", "fabrication" %}
{% for post in fab %}
  {% include archive-single.html %}
{% endfor %}

---

## Personal Projects
Some things I’ve built outside of class:

{% assign personal = site.portfolio | where: "category", "personal" %}
{% for post in personal %}
  {% include archive-single.html %}
{% endfor %}

