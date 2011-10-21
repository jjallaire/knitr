---
layout: default
title: Demo 
---

<div id="home">
  <h1>Archive ({{ site.posts | size }} demos)</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  
</div>
  
