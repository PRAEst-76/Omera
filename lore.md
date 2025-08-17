---
title: Lore
categories: lore
layout: page
---
# Omera Lore

<div class="menu">
  {% for post in site.categories.lore %}
        <p><a href="{{ site.baseurl }}{{ post.url }}">
          {{ post.title }}
        </a></p>
  {% endfor %}
</div>
