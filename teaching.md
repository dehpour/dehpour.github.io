---
layout: page
permalink: /teaching/
title: Teaching
---

{% for post in site.categories.teaching %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
