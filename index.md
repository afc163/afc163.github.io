---
layout: page
---

<ul class="posts">
  {% for post in site.posts %}
    <li>
    <h2><a href="{{ BASE_PATH }}{{ post.url }}>{{ post.title }}</a></h2>
    <span>{{ post.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>

