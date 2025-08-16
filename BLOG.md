---
layout: blog
title:  Blog
permalink: /blog/
---

# Blog

<div>
    {% for post in site.posts %}
      <li>
	  <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
</div>
