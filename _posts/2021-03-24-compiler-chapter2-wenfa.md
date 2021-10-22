---
layout: post
title: "compiler chapter2 wenfa"
subtitle: "编译原理第二章 文法"
date: 2021-03-24
author: "litrane"
header-img: "img/post-bg-2015.jpg"
tags: []
---
# 语法数与文法二义性
**二义性的体现，是文法对同一句子有不止一棵分析树**
这种问题由【句子产生过程中的某些推导有多于一种选择】引起。悬空 else 问题就可以很好地体现这种【超过一种选择】带来的二义性问题，示例如下。
![20210324221514](https://raw.githubusercontent.com/litrane/picbase/master/pic/20210324221514.png)
解决办法：核心：把优先级和结合性说明白

[文法二义性](https://juejin.cn/post/6844904169636102152)
[文法二义性博客](https://blog.csdn.net/weixin_44143695/article/details/103229044)

![20210324221837](https://raw.githubusercontent.com/litrane/picbase/master/pic/20210324221837.png)
上图越往下走优先级越高
