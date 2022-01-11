---
layout: post
title:  Ubuntu 20.04 通过Docker一键安装Redash
date:   2021-05-03 14:31:00 +0800
categories: PRD
description: Ubuntu 20.04上，用Docker最简单安装Redash的方法
permalink: /prd/files/2021/05/03/redash-install-ubuntu-doker.html
tags: 
    - Redash
    - Docker
    - Ubuntu
    - Install
    - getredash
---

{% raw %}<div class="post-summary">{% endraw %}

Ubuntu 20.04上，用Docker最简单安装Redash的方法

{% raw %}</div>{% endraw %}

<!-- more -->

<style type="text/css">
.post-summary { display: none; }
</style>

使用官方的辅助工程进行安装，不用再去麻烦配置Docker,node.js
# 1. 安装 Git

# 2. 下载辅助工程

```bash
git clone https://github.com/getredash/setup.git
```

# 3. 执行安装
运行 Setup 文件夹中 setup.sh 文件。
如果有报错，试试通过 bash 命令来执行 setup.sh 安装：
```bash
bash setup.sh
```

# 4. 设置 Redash
- 安装完成后，可以通过 `local:5000` 访问 redash
- 已经默认设置为外部可以通过 `80` 端口进行访问，所以直接把域名解析到对应服务ip就可以访问