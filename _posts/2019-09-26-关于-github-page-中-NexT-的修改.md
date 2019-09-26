---
title: 关于 github page 中 NexT 的修改
date: 2019-09-26 19:08:00
category: github
tags: [github, blog]
---

## 一、关于 Jekyll 的 tag 与 category

​	在原 NexT 的模板中，tag 与 category 的样式在一个新手看来有点奇怪，在我试图更改某篇默认博文的 tags 后，发现它 404 ERROR 了，在几经折腾后，在 Jekyll 的中文文档了解到了 tag 与 category 的另一种写法，经测定，有效，以本博文为例，下图格式是可行的。
```
title: 关于 github page 中 NexT 的修改
date: 2019-09-26 19:08:00
category: github
tags: [github, blog]
```

​	在本模板的中，只要修改某博文的 tag 和 category ，就会在主页中有所显现。

## 二、关于 NexT 模板中右侧的简介修改

​	这个修改一开始并不知道在哪里，通过百度搜索到了对 NexT 相关修改的操作，发现这个修改是在 _config.yml 文件中的，具体如下图:

![figure1](https://raw.githubusercontent.com/WinterZCDong/WinterZCDong.github.io/master/assets/images/figures/figure1.png)

​	修改相关内容即可。

## 三、修改 NexT 模板中右侧的头像

​	这个比较简单，用自己想换的头像，转换为 gif 格式，更换名字为 "avatar.gif" 并 替换 assets/images 目录下该文件，在 github 上进行更新即可。