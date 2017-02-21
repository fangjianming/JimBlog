---
layout:     post
title:      "Welcome to my blog"
subtitle:   " \"Hello World, Hello Blog\""
date:       2017-02-13 22:11:08
author:     "JimmyFang"
header-img: "post-bg-2017.jpg"
tags:
    - 产品观
---

## 前言

Jimmy 的 Blog 就这么开通了，2017 年，Jimmy总算有个地方可以好好写点东西了;

## 正文

接下来说说搭建这个博客的技术细节,主要借助的是[Hexo](https://pages.github.com/)的快速Building Blog 的技术方案，非常轻松时尚，下面主要介绍一下如何快速搭建:

- 利用NPM安装Hexo，我借助的我强大的阿里巴巴源，安装速度非常快速`cnpm install hexo-cli -g`,如果是是Mac OS下的话，记得取得Root权限，推荐`sudo cnpm install hexo-cli  -g`；
- 一个博客的UI设计风格也是非常重要的一个环节，所以在搜索了GitHub后，发现了一个不错的主题[hexo-theme-huxblog](https://github.com/Kaijun/hexo-theme-huxblog)，所以借鉴使用，在此特别感谢。
- 按照Hexo部署要求，安装hexo-deployer-git，直接`cnpm install hexo-deployer-git --save`，接着需要在`_config.yml`修改为git部署配置，相关配置如下：
```
deploy:
  type: git // 类型
  repo: <repository url> //库（Repository）地址
  branch: [branch] // 分支名称。如果您使用的是GitHub的话，程序会尝试自动检测
  message: [message] // 自定义提交信息 (默认为 Site updated: {{ now('YYYY-MM-DD HH:mm:ss') }})
```
最后执行`hexo deployer`，Hexo会部署至repo相关处，JimBlog借助GitHub个人博客站点；

## 后记

Jimmy非常期待与大家分享个人所得，能够帮助到您的话，那么我会非常开心！！！

   ———— Jimmy 写于浙江杭州


