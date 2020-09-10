---
layout: page
title:  "09-010笔记"
subtitle: "客户端向服务端发送请求的过程"
date:   2020-9-10 10:10:20 +0530
categories: ["正言"]
---

# 客户端向服务端发送请求的过程

- 双方
    - 客户端:发送请求的软件
    - 服务端:接收请求的软件
- 过程
    - hosts文件中寻找域名IP的映射关系
    - 路径：C:\Windows\System32\drivers\etc\hosts
    - 去DNS服务器中找，如果本地hosts文件找不到
    - 在本地hosts写的映射关系称之为静态路由IP与域名
        - 全民公用dns服务器（114.114.114.114）
        - 手机dns改为（8.8.8.8）,会提升速度