---
layout: page
title: Posts
permalink: /blog/
---

<div>
  <ul>
    {% for post in site.posts %}
    <li><h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3></li>
    {% endfor %}
  </ul>
</div>
