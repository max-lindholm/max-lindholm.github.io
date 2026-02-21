---
layout: home
title: "My Blog"
---

# Recent Posts

{% for post in site.posts %}
  ### [{{ post.title }}]({{ post.url }})
  *Published on {{ post.date | date_to_string }}*
{% endfor %}
