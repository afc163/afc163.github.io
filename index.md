---
layout: default
title: 足跡偏右
---

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <h2 class="post-title"><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
      <p class="post-date">{{ post.date | date_to_string }}</p>
      {{ post.content }}
    </li>
  {% endfor %}
</ul>

