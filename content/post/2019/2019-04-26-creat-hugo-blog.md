---
title: "hugo + Github Pages 搭建个人博客"
date: 2019-04-25T13:06:49+08:00
draft: true
description: ""
tags: ["Hugo","blog"]
categories: ["技术"]
---

<!--more-->
Building sites … WARN 2019/04/25 13:19:46 Page's .Hugo is deprecated and will be removed in a future release. Use the global hugo function.
WARN 2019/04/25 13:19:46 Page's .RSSLink is deprecated and will be removed in a future release. Use the Output Format's link, e.g. something like:
    {{ with .OutputFormats.Get "RSS" }}{{ .RelPermalink }}{{ end }}.
WARN 2019/04/25 13:19:46 Page's .URL is deprecated and will be removed in a future release. Use .Permalink or .RelPermalink. If what you want is the front matter URL value, use .Params.url.




[https://gohugo.io](https://gohugo.io/)

Hugo is a fast and modern static site generator written in Go, and designed to make website creation fun again.

## hugo 安装

安装 [git](http://git-scm.com/)

git version

安装 [go](https://golang.org/dl/)

go version

mac 安装 hugo 

brew install hugo 

hugo version

windows

https://github.com/gohugoio/hugo/releases

https://gohugo.io/getting-started/installing

## 建立 hugo 项目

hugo new site [project-name]

hugo new site blog

```
.
├── archetypes
├── assets
├── config
├── content
├── data
├── layouts
├── static
└── themes
```


## 添加主题

cd blog
git clone https://github.com/olOwOlo/hugo-theme-even themes/even


config.yaml
## 添加新博客

hugo new post/my-first-blog.md

## 启动hugo

hugo server

