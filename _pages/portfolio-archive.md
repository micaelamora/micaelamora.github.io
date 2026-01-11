---
title: Portfolio
layout: single
permalink: /portfolio/
classes: wide
---
## Digital Fabrication Projects
My digital fabrication projects:

<div class="entries-grid">
{% assign fab = site.portfolio | where: "category", "fabrication" %}
{% for post in fab %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>

---

## Personal Projects
Some things I’ve built outside of class:

<div class="entries-grid">
{% assign personal = site.portfolio | where: "category", "personal" %}
{% for post in personal %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>

