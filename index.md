---
layout: default
---

# Mike Mitchell

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
