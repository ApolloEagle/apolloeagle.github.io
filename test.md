---
layout: page
title: Test
permalink: /test/
---

<div class="posts">
  <ul>
  {% for post in site.posts %}
    <article class="post">
      <h2>
        <li>
          <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
          <div class="post-date">{{ post.date | date: "%B %e, %Y" }}</div>
        </li>
      </h2>
    </article>
    {% endfor %}
  </ul>
</div>
