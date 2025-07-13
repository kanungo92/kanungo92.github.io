---
layout: default
title: Surf my blogs.
---
# Surf my <span class="highlight-blue">blogs</span>
<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%B %-d, %Y" }} - </span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
