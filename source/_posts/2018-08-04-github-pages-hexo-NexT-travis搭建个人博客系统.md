---
title: github pages + hexo(NexT) + travis搭建个人博客系统
date: 2018-08-04 17:19:39
tags: 
    - github pages 
    - hexo(NexT) 
    - travis 
categories: 
    - other
copyright: true
---
    本文主要分为四个部分介绍如何自动化部署搭建个人博客系统。
    
<!-- more -->
# 本地环境搭建
   需要环境：node(npm)、git
        node的安装
            mac的node，前往[node官网下载](https://nodejs.org/en/download/)。下载pkg，点开文件，一路next，node就安装好了。
            测试是否安装lnode，
            打开terminal，输入node -v
            {% img /images/node.jpg %}
        git的安装
# 本地搭建博客框架(hexo)
    hexo命令的安装: npm install -g hexo
    本地搭建个人博客系统
        初始化一个工程：hexo init <project name>, 如 hexo init blog
        切换到该目录下：cd blog
        安装依赖： npm install
# 手动部署到github pages
    github的注册
    创建github的项目
# 版本控制(github)和持续集成(travis)
    版本控制
    持续集成
        持续集成采用的travis

参考文档：
    1、{% link hexo官方文档 "https://hexo.io/zh-cn/docs/" [external] %}
    2、{% link next官方文档 "http://theme-next.iissnan.com" [exterrnal] %}