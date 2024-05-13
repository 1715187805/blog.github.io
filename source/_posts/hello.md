---
title: Hi Hexo
categories: IT技术
sticky: 100
comments: true
toc: true
expire: true
only:
  - home
  - category
  - tag
tags:
  - Hexo 
  - Blog
pic:
---


pic : 可以指定这篇文章是否使用自定义的缩略图名称（在文章资源文件夹内），而不是使用随机化的图标

sticky : (number)重要的文章，把它们置顶吧！数字越大优先级越高哦~

comments : (true/false)是否为单篇文章指定开启或关闭评论区

toc： (true/false)该文章是否需要生成目录

only： 指定文章显示的位置，有以下关键词：

home: 在首页显示
category: 在分类页显示
tag: 在标签页显示 留空或是不配置此项，则文章在所有该出现的位置都会显示。 层级之间相互平等，没有覆盖关系。 特别地，如果配置了此项，但是使用的并不是以上的关键词（例如只留了一个- none，那么文章就被隐藏起来了）


```
title: 文章标题
date: 2018-03-24 15:31:36
categories: Demo
tags:
- Tag0
- Tag1
- Tag2
sticky: 100
pic:
comments: true
toc: true
expire: true
only:
- home
- category
- tag
```