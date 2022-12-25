---
layout: page
title: Test Page
food: Pizza
---

# /main/about.md
- This is about page.
- URL Path is /main/about
- food: {{ page.food }}
- Posts Index
{% for post in site.posts %}
    * [{{ post.title }}]({{ post.url }})
{% endfor %}
----
