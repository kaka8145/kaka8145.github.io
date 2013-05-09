---
layout: post
title: "3，如何提交代码到github上 "
description: "3，如何提交代码到github上 "
category: note
tags: [note]
---
{% include JB/setup %}

1:安装github for windows
2：打开cmd控制台，进入到D盘文件夹下
3：创建本地库
mkdir my_homework
git init
notepad README.md
git add .
git commit -m 'my first commit'
4：配置远程库
git remote add origin
git push -u origin master