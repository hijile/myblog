---
layout: page
description: "Thinking will not overcome fear but action will."
---

{% include JB/setup %}

## 我的帖子

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

