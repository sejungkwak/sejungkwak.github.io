---
layout: single
title: "Web Development"
permalink: /wd/
---

{% for post in site.wd %}
  {% unless post.path contains "index.md" %}
  - [{{ post.title }}]({{ post.url }})
  {% endunless %}
{% endfor %}