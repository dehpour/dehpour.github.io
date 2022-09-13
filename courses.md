---
layout: page
permalink: /courses/
title: Courses
---

{% for post in site.categories.courses %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
