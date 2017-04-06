---
layout: default
title: My blog
---

# Hi there, you are on _my Blog_ page!
A list of my personal blog posts. There is no actual content at the moment ...

{% for post in site.posts %}
  <!-- Do not indent more than 4 spaces, otherwise Markdown will interpret the line as a block code  -->
  * {{ post.date | date_to_string}} » [{{ post.title }}]({{ post.url }} "{{ post.title }}")
{% endfor %}
