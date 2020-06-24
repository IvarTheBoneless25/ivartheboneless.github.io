---
layout: default
title: Ivar The Boneless Blog
---

# Blog posts

| Date | Title |
|---|---|
{%- for post in site.posts %}
|{{ post.date|date_to_long_string }} | [{{ post.title }}]({{ post.url }})|
{%- endfor %}