---
layout: page
title: Posts
permalink: /blog/
---

<div class="posts">
  {% for post in site.posts %}
  <article class="post">
    <li><h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2></li>

    <div class="excerpt">
      <div class="entry">{{ post.excerpt }}</div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </div>

  </article>
  {% endfor %}
</div>
