---
layout: default
title: 博客
permalink: /blog/
---

<div class="blog-page">
  <h1 class="page-heading">博客</h1>
  <p class="blog-subtitle">记录学习、思考与成长</p>

  {%- if site.posts.size > 0 -%}
  <ul class="post-list">
    {%- for post in site.posts -%}
    <li>
      {%- assign date_format = "%Y-%m-%d" -%}
      <span class="post-meta">{{ post.date | date: date_format }}</span>
      <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
      {%- if post.excerpt -%}
      <p class="post-excerpt">{{ post.excerpt }}</p>
      {%- endif -%}
    </li>
    {%- endfor -%}
  </ul>
  {%- else -%}
  <div class="empty-state">
    <p>博客文章整理中，敬请期待...</p>
  </div>
  {%- endif -%}
</div>