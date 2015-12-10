---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

## Tech

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


### Todos

 - Write Tests
 - Rethink Github Save
 - Add Code Comments
 - Add Night Mode
