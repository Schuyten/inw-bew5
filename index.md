---
layout: default
title: Home
---

# Python Basics

Welkom bij de cursus informaticawetenschappen!

## Hoofdstukken

{% for page in site.pages %}
  {% if page.path contains 'chapters/' %}
    - [{{ page.title }}]
  {% endif %}
{% endfor %}