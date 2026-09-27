---
layout: default
title: Writing
summary: Notes by Seyone Chithrananda on science, biotechnology, and ideas around them.
---

<h1>Writing</h1>
<p>A few older pieces on science and biotechnology, hosted on Medium.</p>
<ul class="posts">
  {% for post in site.posts %}
  <li><a href="{% if post.external_url %}{{ post.external_url }}{% else %}{{ post.url }}{% endif %}">{{ post.title }}</a> <span class="post-date">{{ post.date | date: "%Y" }}{% if post.external_host %} · {{ post.external_host }}{% endif %}</span></li>
  {% endfor %}
</ul>
