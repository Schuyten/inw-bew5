---
layout: default
title: Home
---

# Python Programming Basics

Welcome to the course on Python programming basics!

## Chapters

{% for page in site.pages %}
  {% if page.path contains 'chapters/' %}
    - [{{ page.title }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}