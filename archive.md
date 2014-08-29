---
layout: page
title: Archive
---

## DiPP Posts

{% for post in site.posts %}
  * {% if post.eventdate %}{{ post.eventdate | date_to_string }}{% else %}{{ post.date | date_to_string }}{% endif %} &nbsp;&nbsp; [ {{ post.title }} ]({{ post.url }}) &nbsp;&nbsp; {% for c in post.categories %}&nbsp;{% if c == 'haha'%}Hack Harris{% elsif c == 'event' %}Events{% elsif c == 'newsletter' %}Newsletter{% endif %}&nbsp;{% endfor %}
{% endfor %}
