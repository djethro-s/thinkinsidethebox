---
layout: default
---

## New Day, New Idea (Maybe)

{% for post in site.posts %}
- {{ post.date | date: "%d %m %Y" }} — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
