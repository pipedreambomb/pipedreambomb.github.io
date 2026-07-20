---
layout: default
title: Home
---

Hi, I'm George. This is where I write up fixes, opinions, and things I've puzzled out — often with an LLM's help.

<ul>
  {% for post in site.posts %}
    <li>
      <small>{{ post.date | date: "%-d %B %Y" }}</small>
      &mdash;
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
