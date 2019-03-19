---
layout: page
title: Aaronsz' Blog
tagline: Welcom!
---

<ul class="nav navbar-nav">
  {% assign pages_list = site.pages %}
  {% assign group = 'navigation' %}
  {% include JB/pages_list %}
</ul>

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>