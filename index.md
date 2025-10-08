---
layout: default
---

{% for post in site.posts %}
<p style="margin-bottom: 0;"><small>{{ post.date | date: "%B %d, %Y" }}</small></p>

## [{{ post.title }}]({{ post.url | relative_url }})

{% endfor %}
<p style="margin-top: 2em;"><small>subscribe <a href="{{ "/feed.xml" | relative_url }}">via RSS</a></small></p>
