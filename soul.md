---
layout: postindex
title: SOUL
permalink: /soul/
---


<div class="page-heading">SOUL</div>
<ul class="default-list">
{% for post in site.categories['soul'] %}
  <li>
    <span class="default-meta">{{ post.date | date: "%m/%d/%Y" }} - </span>
    <a class="default-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
