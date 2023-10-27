---
title: "带有图片资源的推荐示例文章"
description: 本示例使用页面图片资源作为特色图片，该图片将会被用于幻灯片和列表。
date: 2022-02-04T20:26:48+08:00
draft: false
featured: true
series:
  - 指南
categories:
  - 文章
tags:
  - 特色图片
authors:
  - HB
---

要使用页面图像资源作为特色图像，您需要将图像放在页面的文件夹中，并以 `*feature*`, `*cover*` 或 `*thumbnail*` 模式命名，例如。

```sh
$ tree content/blog/featured-image-resource 
content/blog/featured-image-resource
├── featured.jpeg
├── index.en.md
└── index.zh-hans.md
```
