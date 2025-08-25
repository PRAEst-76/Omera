---
layout: page
---
<h2>Commit History</h2>
<ul>{% for message in page.commit_messages %}
  <li>{{ message }}</li>{% endfor %}
</ul>