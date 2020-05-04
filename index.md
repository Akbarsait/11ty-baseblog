---
layout: layouts\layout.njk
date: 2020-01-08
---


# {{ title }}
Hello, world!

{% for post in collections.post %}
- [{{ post.data.title }}]({{ post.url}})
{% endfor %}