---
layout: page
title: Posts
permalink: /blog/
---

<div class="posts">
  {% for post in site.posts %}
  <article class="post">
    <h2><li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li></h2>

    <div class="excerpt">
      <div class="entry">{{ post.excerpt }}</div>
      <h5><a href="{{ site.baseurl }}{{ post.url }}">Read More</a></h5>
    </div>

  </article>
  {% endfor %}
</div>
