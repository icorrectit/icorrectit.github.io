---
layout: default
title: I Correct It
---

## Coming Soon.

The Internet needs some grammatical guidance. I'm here to help. (Or I will be, shortly.)

### Pages

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url | prepend: site.baseurl }}) ({{ post.date | date: "%b %-d, %Y" }})
{% endfor %}
