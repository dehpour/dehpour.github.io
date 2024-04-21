---
layout: page
permalink: /notes/
title: Notes
---
<p>These are the notes I’ve taken while learning physics. They’re quite compact and don’t usually correspond closely with any particular course; instead, they’re packed full of all the neat things I’ve found reading books.</p>

{% for post in site.categories.notes %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
