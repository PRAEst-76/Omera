---
title: Categories
layout: default
---
# Categories
{% for category in site.categories %}
  <p>{{ category[0] }}</p>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title | capitalize }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

