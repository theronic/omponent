---
layout: default
title: Testing 123
---

{%for cat in site.categories %}
  cat: {{ cat }}<br />
{% endfor %}

{% for post in site.categories.components %}
title: {{ post.title }}<br />
{% endfor %}
