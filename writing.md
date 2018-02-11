---
layout: page
permalink: /writing/
title: writing
description: 
---

<ul class="post-list">
{% for post in site.posts %}
    <li>
        <h2><a class="post-list-title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
        <p class="post-meta">{{ post.date | date: '%B %-d, %Y' }}</p>
      </li>
{% endfor %}
</ul>