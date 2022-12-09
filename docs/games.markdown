---
layout: default
title: Games
description: "Links to all our games"
---

<ul>
  {% for game in site.games %}
    <li>
      <h2><a href="{{ game.url }}">{{ game.name }}</a></h2>
      <h3>{{ game.position }}</h3>
      <p>{{ game.excerpt }}</p>
    </li>
  {% endfor %}
</ul>