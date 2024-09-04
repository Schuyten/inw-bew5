---
layout: default
title: Home
---

# Informaticawetenschappen BEW5

Welkom bij de cursus informaticawetenschappen!

## Hoofdstukken

{% for page in site.pages %}
  {% if page.path contains 'chapters/' %}
    - [{{ page.title }}]
  {% endif %}
{% endfor %}