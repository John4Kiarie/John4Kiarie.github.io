---
layout: default
title: Home
---

# {{ site.title }}

Welcome — this is a collection of TryHackMe / Hack The Box writeups.

## Recent posts
<ul>
{% for post in site.posts limit:6 %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%Y-%m-%d" }}</li>
{% endfor %}
</ul>

Go to [Writeups](/writeups/) to see all posts.
