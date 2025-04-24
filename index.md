---
layout: layout.njk
title: My Rad Markdown Blog Post
---
{% for post in collections.post %}
<h2>{{ post.data.title }}</h2>
<p>{{ post.content }}</p>
{% endfor %}
