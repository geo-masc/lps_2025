---
layout: default
title: Living Planet Symposium 2025
---

<link rel="stylesheet" href="/assets/style.css">

# My Sessions

<ul>
{% assign sorted_sessions = site.data.sessions | sort: "date" %}
{% for session in sorted_sessions %}
  <li>
    <strong>{{ session.title }}</strong><br>
    Date: {{ session.date }}<br>
    Time: {{ session.time }}<br>
    Location: {{ session.location }}
  </li>
{% endfor %}
</ul>
