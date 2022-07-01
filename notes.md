---
layout: page
permalink: /notes/
title: Personal Notes
---
{% for post in site.categories.notes %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
