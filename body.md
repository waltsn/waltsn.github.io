---
layout: postindex
title: BODY
permalink: /body/
---

<div class="page-heading">BODY</div>
<ul class="default-list">
{% for post in site.categories['body'] %}
  <li>
    <span class="default-meta">{{ post.date | date: "%m/%d/%Y" }} - </span>
    <a class="default-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
