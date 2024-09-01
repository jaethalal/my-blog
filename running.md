---
layout: page
title: Running
permalink: /running/
---

Here you'll find all my posts related to Running.

{% for post in site.categories.running %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}