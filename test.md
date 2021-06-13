---
layout: page
title: Test
permalink: /test/
---

<div class="posts">
  <ul>
  {% for draft in site.drafts %}
    <article class="draft">
      <h2>
        <li>
          <a href="{{ site.baseurl }}{{ draft.url }}">{{ draft.title }}</a>
          <div class="post-date">{{ draft.date | date: "%B %e, %Y" }}</div>
        </li>
      </h2>
    </article>
    {% endfor %}
  </ul>
</div>
