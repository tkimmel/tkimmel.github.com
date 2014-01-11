---
layout: page
title: WIP Site
tagline: This is Jekyll.  I'm still playing with it.
---
{% include JB/setup %}
<head>
    <link rel="stylesheet" href="animate.min.css">
</head>

<div style="height: 100px; width: 100px; background-color: #000;"> hai </div>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



