---
layout: default
title: Home
---

Hi, I'm George. This is where I write up fixes, opinions, and things I've puzzled out — often with the help of an LLM - and then written up here (again with the help of an LLM, but edited by me, a human) in case it helps someone else not have to bother. Or maybe jokes or something, I dunno, we'll see.

<h2>Recent posts:</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <small>{{ post.date | date: "%-d %B %Y" }}</small>
      &mdash;
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
