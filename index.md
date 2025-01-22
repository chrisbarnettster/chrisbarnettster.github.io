---
layout: default
title: Home
---

# Welcome to My Blog!

This is the homepage of my blog.

Check out my latest posts:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}
