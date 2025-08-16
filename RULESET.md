---
title: Omera Ruleset
permalink: /ruleset/
---

<ul>
{% for page in site.pages %}
    <li><a href="{{ page.url }}">{{ page.title}}</a>
    <span class="pageDate">{{ page.date | date: "%b %-d, %Y" }}</span>
    </li>
{% endfor %}
</ul>
