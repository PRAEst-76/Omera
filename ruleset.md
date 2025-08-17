---
title: Omera Ruleset
layout: ruleset
---
# Ruleset

(insert 90's "Under Construction" animated gif here)
<div class="posts">
  {% for post in site.categories.ruleset %}
        <p><a href="{{ post.url | relative_url }}">
          {{ post.title }}
        </a></p>
  {% endfor %}
</div>
