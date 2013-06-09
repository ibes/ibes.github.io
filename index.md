---
layout: default
header : Sebis Blog
title: Sebis Blog
tagline: Sebis Gedankenwelt
---
{% include JB/setup %}

<ul>
  {% for post in site.posts %}
  <li>
		<span>{{ post.date | date: "%B %e, %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>


