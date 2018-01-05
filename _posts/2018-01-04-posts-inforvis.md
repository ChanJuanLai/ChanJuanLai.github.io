---
layout: archive
title: "信息可视化心得"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "抓取数据的分析"
tags: []
image: 
  feature: tableau.png
  teaser: tableau.png
---

这张图是从全国各省抓取的五大珠宝品牌的数据，然后在tableau进行分析的结果。
1. 首先要个高德地图的个人Key
2. 然后可以用老师给的代码，一步步跑，把自己几个关键词所需要的数据跑出来
3. 跑出数据后，会发现原来有代码的文件夹里面会有出现一个tsv档
4. 然后把这个tsv档读进tableau，之后改经度纬度为地理位置
5. 然后就可以转到工作表里面，把经度纬度放进行列，放进去之后要记得把经度纬度设置为维度，做成地图。
6.之后还有做各种图形，比如条形图，表格等等的就自己做啦。
最后最后！推荐大家去看tableau官网的教学视频！很有用的哟！
<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->
