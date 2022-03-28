---
layout: page
title: Portfolio
permalink: /portfolio/
---

{% for project in site.portfolio %}

  <h2>{{ project.name }}</h2>
  <p>{{ project.content | markdownify }}</p>
{% endfor %}
