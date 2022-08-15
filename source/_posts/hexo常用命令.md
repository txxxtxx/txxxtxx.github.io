---
title: hexo常用命令
date: 2022-08-15 18:08:37
categories:
- hexo
---


hexo搭建的博客，很久不动又会忘记步骤，这里记录一下

### 下载
从github上面把代码下载下来，hexo分支是源码，master是生成的静态文件

### 初始化
进入到目录，执行命令进行初始化

``` bash
$ cd <hexo blog folder>
$ npm install
$ hexo g
$ hexo s
```

>浏览器打开[localhost](http://localhost:4000/)，查看是否启动成功

### 写文章
Hexo 有三种默认布局：`post`、`page` 和 `draft`，[详见](https://hexo.io/zh-cn/docs/writing)
 
```bash
  # 创建一个草稿
$ hexo new draft "title"
  # 直接创建文章
$ hexo new "title"
  # 发布
$ hexo publish "title"
```
