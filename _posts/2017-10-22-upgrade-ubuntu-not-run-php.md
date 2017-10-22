---
title: "升级Ubuntu 17.10导致php异常"
excerpt: "Post displaying how to resolve can not run php with upgrade ubuntu."
header:
  teaser: "assets/images/markup-syntax-highlighting-teaser.jpg"
tags: 
  - php
  - apache2
categories:
  - WEB Development
---

# 问题描述
    从Ubuntu 17.05升级到Ubuntu 17.10后，在浏览器中只能显示PHP源码。

# 解决方法
    ```shell
    a2enmode php7.1
    sudo service apache2 restart
    ```
