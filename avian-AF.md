---
layout: page
title: avian-AF
---

## avian-AF posts

{% for post in site.posts %}
  {% for tag in post.tags %}
    {% if tag == "avian-AF" %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.baseurl }}{{ post.url }})

     {{ post.summary }}...
    {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}