---
layout: default
title: Aaronsz' Personal Site
---

# Hi there, I'm Aaronsz Xia!

I am a student of Nanjing University of Posts and Telecommunications by day, and a programmer by night.

It is my personal website and currently being updated not so actively, cause I am preparing for the postgraduate entrance examination.

## Here's the posts list:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>