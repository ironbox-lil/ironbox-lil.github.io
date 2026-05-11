---
layout: default
title: 博客
permalink: /blog/
---

<div class="page-content">
  <h1 class="page-heading">博客</h1>
  <p class="page-subtitle">记录学习、思考与成长</p>

  {%- if site.posts.size > 0 -%}
  <ul class="post-list">
    {%- for post in site.posts -%}
    <li>
      {%- assign date_format = "%Y-%m-%d" -%}
      <span class="post-meta">{{ post.date | date: date_format }}</span>
      <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
      </h3>
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

<style>
.page-subtitle {
  color: #888;
  margin-top: -1.5rem;
  margin-bottom: 2rem;
  font-size: 1.1rem;
}
.empty-state {
  text-align: center;
  padding: 3rem;
  color: #888;
  background: #f8f9fa;
  border-radius: 12px;
}
.post-excerpt {
  color: #666;
  margin-top: 0.5rem;
  font-size: 0.95rem;
}
</style>