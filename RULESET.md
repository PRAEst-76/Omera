---
title: Omera Ruleset
permalink: /ruleset/
---

# Ruleset


<div>
   {% for page in site.pages %}
    	<p><a href="{{ page.url }}">{{ page.title}}</a>
    	<span class="pageDate">{{ page.date | date: "%b %-d, %Y" }}</span>
    	</p>
   {% endfor %}
</div>
