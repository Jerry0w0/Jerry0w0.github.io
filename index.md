---
layout: default
title: 我的博客首页
---

<h1>📝 文章列表</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color:#999; font-size:14px;">（{{ post.date | date: "%Y年%m月%d日" }}）</span>
    </li>
  {% endfor %}
</ul>

<p>欢迎来到我的个人博客！</p>
