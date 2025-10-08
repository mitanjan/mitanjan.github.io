---
layout: default
title: About
---

{% for post in site.posts %}
<p style="margin-bottom: 0;"><small>{{ post.date | date: "%B %d, %Y" }}</small></p>

## [{{ post.title }}]({{ post.url | relative_url }})

{% endfor %}
