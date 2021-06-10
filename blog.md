---
layout: page
title: Posts
permalink: /blog/
---

<div class="posts">
  <ul>
  {% for post in site.posts %}
    <article class="post">
      <h2>
        <li>
          <div class="post-image">
              {% include donut.html %}
          </div>
          <div>
            <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
            <div class="post-date">{{ post.date | date: "%B %e, %Y" }}</div>
          </div>
        </li>
      </h2>
    </article>
    {% endfor %}
  </ul>
</div>
