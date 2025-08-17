---
title: Lore
categories: lore
---
# Omera Lore

<div class="posts">
  {% for post in site.categories.lore %}
        <p><a href="{{ site.baseurl }}{{ post.url }}">
          {{ post.title }}
        </a></p>
  {% endfor %}
</div>
