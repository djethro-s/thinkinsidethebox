---
layout: default
---

## Dokumen Bocor / Postingan Terbaru

{% for post in site.posts %}
- {{ post.date | date: "%d %b %Y" }} — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
