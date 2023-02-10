---
title: Leigh Capili's Blog
layout: _base
---

|  |  |
|--|--:|
{%- for post in collections.post reversed %}
|  **[{{ post.data.title }}]({{ post.url }})** | {{ post.data.page.date | postDate }} |
{%- endfor %}
