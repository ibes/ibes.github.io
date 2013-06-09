---
layout: page
title: Sebis Blog
tagline: Sebis Gedankenwelt
---
{% include JB/setup %}
<div class="content">
  <div class="related">
    <ul>
      {% for post in site.posts %}
      <li>
	<span>{{ post.date | date: "%B %e, %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
      {% endfor %}
    </ul>
  </div>
</div>