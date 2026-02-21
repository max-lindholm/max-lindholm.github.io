---
layout: home
title: "Welcome to my blog"
---
# Recent Posts
{% for post in site.posts %}
  ### [{{ post.title }}]({{ post.url }})
  *Published on {{ post.date | date_to_string }}*
{% endfor %}

