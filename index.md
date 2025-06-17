---
layout: default
title: Living Planet Symposium 2025
---

# My Sessions

<ul>
{% for session in site.data.sessions %}
  <li>
    <strong>{{ session.title }}</strong><br>
    Date: {{ session.date }}<br>
    Time: {{ session.time }}<br>
    Location: {{ session.location }}
  </li>
{% endfor %}
</ul>
