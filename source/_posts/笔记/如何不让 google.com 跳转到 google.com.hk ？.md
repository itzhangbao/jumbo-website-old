
title: 如何不让 google.com 跳转到 google.com.hk ？
date: 2017-08-15 10:09:15
tags: 笔记

---

![](http://upload-images.jianshu.io/upload_images/1874013-7e6181e573f20f49.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 前言

> 自从google的服务器搬离中国大陆后，大陆地区用户用 google 服务时会自动跳转到香港的 **http://google.com.hk** ，有关键字过滤而且偶尔不是很稳定，这对我们的生活工作都造成了困扰。

#### 一、大家可以通过以下的方法访问 **http://google.com**

**1.** 直接用 **http://www.google.com/ncr** ，`ncr` 是 `no country redirection` ，是一个强制不跳转的命令；
**2.** 用 **https://www.google.com/** ，`https` 协议。

#### 二、另外一个问题是Chrome浏览器的默认搜索也是设置为 **http://www.google.com.hk/** ，我们可以自行修改一下。

- Chrome – 设置 -搜索 - 管理搜索引擎 – 其他搜索引擎
- 拉到最下，有一个“添加”
- 名字：自己写，我写 **http://google.com**
- 关键字（keyword），我写 G
- 最后一个空最重要，写入Url ( **http://www.google.com/search?hl=zh-CN&q=%s**) 或者 ( **http://www.google.com/search?q=%s** ) `括号为填写部分`
- 然后将之设置成默认搜索引擎，搞定！

一张图：
![setting of google search.png](http://upload-images.jianshu.io/upload_images/1874013-08decbaacbd350ac.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### ***完！***
> **so easy！**好好享受 ***google*** 原汁原味的搜索吧！
