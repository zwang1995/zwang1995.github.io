---
layout: default
title: "News"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="News" %}
{% endif %}
