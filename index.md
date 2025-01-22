---
layout: default
title: Home
---

# Welcome!

This is the index page of my blog.

Check out my latest posts:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}
