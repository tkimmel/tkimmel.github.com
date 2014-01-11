---
layout: page
title: "Travis' Sandbox"
---

<button type="button" class="btn btn-default latestNotes animated tada">Get the latest meeting notes</button>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



