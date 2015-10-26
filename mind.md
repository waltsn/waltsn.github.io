---
layout: postindex
title: MIND
permalink: /mind/
---


<div class="page-heading">MIND</div>
<ul class="default-list">
{% for post in site.categories['mind'] %}
  <li>
    <span class="default-meta">{{ post.date | date: "%m/%d/%Y" }} - </span>
    <a class="default-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
