---
layout: page
title: Archive
---

## DiPP Posts

{% for post in site.posts %}
{% unless post.categories contains 'haha' %}
  * {{ post.date | date_to_string }} &nbsp;&nbsp; [ {{ post.title }} ]({{ post.url }})
  {% endunless %}
{% endfor %}
