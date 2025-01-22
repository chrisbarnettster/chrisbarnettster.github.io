---
layout: post
title: "Test Post"
date: 2025-01-22
last_modified_at: 2025-01-22 15:42
---

This is a test post! Thanks for viewing move on to the next one :)

<footer>
  {% if page.last_modified_at %}
    <p>Last updated: {{ page.last_modified_at | date: "%B %d, %Y" }}</p>
  {% else %}
    <p>This post has not been updated.</p>
  {% endif %}
</footer>
