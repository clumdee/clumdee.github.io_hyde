---
layout: page
title: Blog entries
---

<!-- Do not indent more than 4 spaces, otherwise Markdown will interpret the line as a block code  -->
{% for post in site.posts %}
  * {{ post.date | date_to_string}} » [{{ post.title }}]({{ post.url }} "{{ post.title }}")
{% endfor %}
