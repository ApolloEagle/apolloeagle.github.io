---
layout: page
title: Posts
permalink: /blog/
---

<div class="posts">
  {% for post in site.posts %}
  <article class="post">
    <h2><li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li></h2>
    <div class="date">{{ page.date | date: "%B %e, %Y" }}</div>
  </article>
  {% endfor %}
</div>
