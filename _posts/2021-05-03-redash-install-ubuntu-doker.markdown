---
layout: post
title:  Ubuntu 20.4 通过Docker一键安装Redash
date:   2021-05-03 14:31:00 +0800
categories: PRD files
description: Ubuntu 20.04上，用Docker最简单安装Redash的方法
keyword: Redash,Docker,Ubuntu,Install,getredash
---

使用官方的辅助工程进行安装，不用再去麻烦配置配置Docker,node.js
# 1. 安装 Git

# 2. 下载辅助工程

```bash
git clone https://github.com/getredash/setup.git
```

# 3. 执行安装
运行 Setup 文件夹中 setup.sh 文件。
如果有报错的化，试试通过 bash 命令来执行 setup.sh 安装：
```bash
bash setup.sh
```