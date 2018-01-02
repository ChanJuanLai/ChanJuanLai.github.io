---
layout: archive
title: "联系我"
date: 2018-01-02T11:40:45-04:00
modified:
excerpt: "关于作者"
tags: []
image: 
  feature: me.jpg
  teaser:
---

- 姓名：赖婵娟
- 专业：网络与新媒体
- E-mail:1277363970@qq.com
- Tel:13532756358
<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->