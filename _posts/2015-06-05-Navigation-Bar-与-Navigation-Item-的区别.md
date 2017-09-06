---
layout: post
title: NavigationBar与Navigation Item的区别
category: tech
tags: iOS
description: 刚接触 iOS 开发的同学估计不清楚 Navigation Bar 和 Navigation Item 区别，我在这里简单介绍一下两者的区别。
keywords: Navigation Bar, Navigation Item, UINavigationController
---

> 刚接触 iOS 开发的同学估计不清楚 Navigation Bar 和 Navigation Item 区别，我在这里简单介绍一下两者的区别。

![1.png](http://upload-images.jianshu.io/upload_images/439444-225bf2491e8f6578.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![2.png](http://upload-images.jianshu.io/upload_images/439444-6e688c6d08c06888.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![3.png](http://upload-images.jianshu.io/upload_images/439444-d6992811be255d6b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![4.png](http://upload-images.jianshu.io/upload_images/439444-645dcec0c866dfae.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![5.png](http://upload-images.jianshu.io/upload_images/439444-2606a108e1406299.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 总结
- Navigation Bar 是 Navigation Controller（容器） 的属性，容器中的多个 View Controller 会共用这一属性；
- Navigation Bar 的作用是放置 Navigation Item；
- Navigation Item 是 View Controller 的独有属性，容器中多个 ViewController 之间不会共用这一属性；
- Navigation Item 的作用是放置 leftBarButtonItem、rightBarButtonItem、title 和 prompt 等。
