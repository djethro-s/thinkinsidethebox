---
layout: default
---

## Think Inside The Box

Hello thinkers,

Welcome to Think Inside The Box. If you're wondering why this exists, it's simple: I wanted to share some thoughts for those of us who wonder how to navigate a system that demands us to be extraordinary, even when we know our capabilities are perfectly average. I'm a Jack of All Trades (JOAT) myself, and I have as many questions as you do. I hope my explorations here bring you some clarity, or at least, a good perspective.

Have a nice wondering!

{% for post in site.posts %}
- {{ post.date | date: "%d %m %Y" }} — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
