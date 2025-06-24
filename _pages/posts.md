---
layout: single
title: Posts
author_profile: true
permalink: /posts/
nav_order: 2
---

Below are my articles and posts. Click to view each as a separate page.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color: gray; font-size: 0.9em;"> – {{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>