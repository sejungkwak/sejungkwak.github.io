---
layout: single
title: "Software Engineering I"
permalink: /se/
---

{% for post in site.se %}
  {% unless post.path contains "index.md" %}
  The content is sourced from lecture slides by Dr. Irene Murtagh and the book *Java: How to Program* by Paul Deitel and Harvey Deitel.
  - [{{ post.title }}]({{ post.url }})
  {% endunless %}
{% endfor %}

