layout: page
title: Test Page
permalink: /main/about
food: Pizza
---

- This is about page.
- URL Path is /main/about
- food: {{ page.food }}
- Posts Index
{% for post in site.posts %}
    * [{{ post.title }}]({{ post.url }})
{% endfor %}
