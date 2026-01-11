---
title: Portfolio
layout: single
permalink: /portfolio/
classes: wide
---

## Digital Fabrication Projects
My digital fabrication projects:

{% assign fab_projects = site.portfolio %}
{% include collection-grid.html collection=fab_projects %}

---

## Personal Projects
Some things I’ve built outside of class:

{% assign personal_projects = site.personal %}
{% include collection-grid.html collection=personal_projects %}

