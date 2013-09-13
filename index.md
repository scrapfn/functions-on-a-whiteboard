---
layout: default
title:  Functions On a Whiteboard
---

{% for post in site.posts limit:5 %}
+ [{{ post.title }}]({{ site.url }}{{ post.url }})
{% endfor %}
