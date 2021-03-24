---
title: tbc blog
date: 2021-02-26 15:53:15
tags: tbc
categories:
- 笔记
---

腾讯云静态网站托管
腾讯云域名购买到实名认证
ssl证书购买到部署

云托管到 网站备案 

备案完成到 静态托管自定义 域名

<!-- cloudbase framework deploy -e "your-env-id" -->
环境下 执行 cloudbase  自动部署

# 部署文件到指定目录
tcb hosting deploy localPath cloudPath -e envId

# 将 hosting 目录下的所有文件部署到根目录
tcb hosting deploy hosting -e envId

# 将 static 目录下的 index.js 文件部署到 static/index.js
tcb hosting deploy ./static/index.js static/index.js -e envId
<!-- more -->