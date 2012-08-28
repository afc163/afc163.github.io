---
layout: default
---

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <h2 class="post-title"><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
      <span class="post-date">{{ post.date | date_to_string }}</span>
      {{ post.content }}
    </li>
  {% endfor %}
</ul>

