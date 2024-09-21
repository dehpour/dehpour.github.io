---
layout: page
permalink: /slides/
title: Slides
---
<p>These are the slides I’ve presented.</p>

{% for post in site.categories.slides %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
