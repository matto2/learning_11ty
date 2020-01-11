---
layout: layout.liquid
title: Welcome to the blog!
---

{% for blog in collections.blog %}
- [{{blog.data.title}}]({{blog.url}})
{% endfor %}

You should read it!