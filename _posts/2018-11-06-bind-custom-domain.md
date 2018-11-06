---
layout: post
title:  "博客bind自己的域名"
date:   2018-11-06 10:49:28
categories: domain
tags: domain
---

* content
{:toc}

## 注册域名

可以去阿里云/腾讯云，或其他域名供应商购买域名，注册前可以到[阿里云](https://wanwang.aliyun.com/domain/com/)
检测一下自己的域名是否已被注册。

##实名认证
域名注册后，需要上传自己的证件信息进行实名认证，这个材料准备好之后一般都很快，我的用的是阿里云，身份证上传好一个小时之内就认证好了。

##域名解析
以阿里云为例，点击域名之后的“解析”， 只需添加两条记录。下面是我的域名和github.io的配置信息
|       |      |          |                  |
| ----- | ---- | -------- | ---------------- |
|       | 域名 | 域名类型 | 域名状态         |
| CNAME | www  | 默认     | jiephe.github.io |
| CNAME | @    | 默认     | jiephe.github.io |

##GitHub Pages 设置
Custom domain 输入自己新建的域名 save之后就可以了
