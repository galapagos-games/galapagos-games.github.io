---
layout: default
title: News
description: "Check here for all the news on our games including upcoming releases"
---
<h1>Latest News</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>