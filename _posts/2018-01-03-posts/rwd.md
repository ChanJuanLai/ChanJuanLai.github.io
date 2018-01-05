---
layout: article
title: "如何搭建属于自己的网站？"
date: 2018-1-03T11:40:45-04:00
modified:
excerpt: "搭建自己的个人网站"
tags: []
image: 
  feature: post3.png
  teaser: post3.png
---
如何搭建属于自己的网站？
1. 先找到一个模板，然后登录自己的GitHub，建立一个仓库，再去他的GitHub仓库里面fork他的模板，再去setting里面改成自己GitHub的username。
2. 然后就可以开始改外观啦！（拿老师的模板来说吧）
- 要改网站的名字的话就在_config.yml里面改。
- 改背景的话，先找到_sass文件，然后就去_base.scss 里面改背景图（背景图要自己上传到image，还要删掉本来的图）
- 要想加多导栏的话，先找到_data文件里面的navigation.yml ，里面有多少段就是有多少个导栏，如果想要多一个就复制一段，然后改名字图片url就好啦。
- 要改想点导栏出来的不是404的话，就要自己写一个md啦，把这个md放进相对应的相同url的文件夹里面。
- 文章的话，就先把老师原来的文章删掉，然后自己写，现在有道云里面写好在放进GitHub里面。
