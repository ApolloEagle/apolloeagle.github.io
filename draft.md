---
layout: page
title: Draft
permalink: /draft/
---

<div class="posts">
  <article class="post">
    <h1>
      <a href="{{ site.baseurl }}{{ site.drafts[0].url }}"
        >{{ site.drafts[0].title }}</a
      >
    </h1>
    <div class="post-date">{{ site.drafts[0].date | date: "%B %e, %Y" }}</div>

    <div class="entry">{{ site.drafts[0].content }}</div>

  </article>
</div>
