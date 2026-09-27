---
layout: default
title: Writing
summary: Notes by Seyone Chithrananda on science, biotechnology, and ideas around them.
---

<p class="section-index">Notes / Archive</p>
<h1>Writing<em>.</em></h1>
<p>Occasional notes on science, biotechnology, and ideas around them. These pieces are from earlier chapters; I hope to add more soon.</p>
<ul class="posts">
  {% for post in site.posts %}
  <li>
    <a href="{% if post.external_url %}{{ post.external_url }}{% else %}{{ post.url }}{% endif %}">{{ post.title }} <span aria-hidden="true">↗</span></a>
    <span class="post-date">{{ post.date | date: "%B %Y" }}{% if post.external_host %} · {{ post.external_host }}{% endif %}</span>
  </li>
  {% endfor %}
</ul>
