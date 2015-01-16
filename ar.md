---
layout: blog
locale: ar
---

{% for post in site.categories.ar %}
### {{ post.title }}
*{{ post.date | date: "%b %-d, %Y" }}*

{{ post.content }}
{% endfor %}
