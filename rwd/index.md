---
layout: archive
title: "Note 笔记"
date: 2018-1-03T23:11:36-04:00
modified:
excerpt: "杂的没什么用的学习纪律"
tags: []
image: 
  feature: 控分大佬1.jpg
  teaser:
---

在此我从《响应式Web设计》中收集到的信息

<div class="tiles">
{% for post in site.categories.SDG %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 SDG 的列出来-->