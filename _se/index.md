---
layout: single
title: "Software Engineering I"
permalink: /se/
---

{% for post in site.se %}
  {% unless post.path contains "index.md" %}
  - [{{ post.title }}]({{ post.url }})
  {% endunless %}
{% endfor %}

