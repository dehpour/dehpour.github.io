---
layout: page
permalink: /notes/
title: Personal Notes
---
<div>Here are a selection of my papers & notes.</div>
{% for post in site.categories.notes %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
