---
title: Portfolio
layout: single
permalink: /portfolio/
classes: wide
---
## Personal Projects
Some things I’ve built outside of class:

<div class="entries-grid grid__item--3">
  {% assign personal = site.portfolio | where: "category", "personal" %}
  {% for post in personal %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

## Digital Fabrication Projects

<div class="entries-grid grid__item--3">
  {% assign fab = site.portfolio | where: "category", "fabrication" %}
  {% for post in fab %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

<div style="clear: both;"></div>






