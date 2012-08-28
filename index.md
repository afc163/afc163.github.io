---
layout: page
---

<ul class="posts">
  {% for post in site.posts %}
    <li>
## [{{ post.title }}]({{ BASE_PATH }}{{ post.url }})
<span>{{ post.date | date_to_string }}</span>
  {% endfor %}
</ul>

