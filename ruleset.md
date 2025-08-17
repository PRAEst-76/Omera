---
title: Omera Ruleset
layout: ruleset
---
# Ruleset

(insert 90's "Under Construction" animated gif here)
<div class="posts">
  {% for post in site.categories.ruleset %}
  <article class="post">
      <h1 class="post-title">
        <a href="{{ post.url | relative_url }}">
          {{ post.title }}
        </a>
      </h1>
      {{ post.content | markdownify | strip_html | truncatewords: 30 }}
    </article>
  {% endfor %}
</div>
