---
layout: page
title: Emilandia!
tagline: Un blog desblogueado 
---
{% include JB/setup %}

**Lista de post**

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


