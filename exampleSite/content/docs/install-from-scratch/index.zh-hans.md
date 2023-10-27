---
title: "从头开始安装"
description: "从头开始使用 HB 卡主题构建快速、响应式和模块化静态网站。"
# linkTitle:
date: 2023-12-02T11:47:31+08:00
draft: false
noindex: false
featured: true
pinned: true
nav_weight: 1
nav_icon:
  vendor: bootstrap
  name: cloud-download
  color: green
series:
  - 文档
categories:
tags:
  - 安装
images:
  - https://res.cloudinary.com/razonyang/image/upload/f_auto/website-design?width=1920&height=1280
# menu:
#   main:
#     weight: 100
#     params:
#       icon:
#         vendor: bs
#         name: book
#         color: '#e24d0e'
authors:
  - HB
  - HugoMods
---

我们提供了一个示例站点以方便你快速入门该主题。

## 环境要求

- Go
- Hugo 扩展版
- Node.js `16` 或更高版本

了解更多关于[先决条件](https://zh-hans.hbstack.dev/docs/getting-started/prerequisites/)的内容。

## 克隆仓库

```sh
git clone --depth 1 https://github.com/hbstack/theme-cards
```

## 复制示例站点

```sh
cp -r theme-cards/exampleSite mysite
```

## 更改工作目录

```sh
cd mysite
```

## 调整 `go.mod`

### 替换模块路径

模块路径是站点的标识，其一般为仓库 URL，这里以 `github.com/user/repo` 为例。

```sh
sed -i '1s/.*/module github.com\/user\/repo/' go.mod
```

### 删除 `replace` 指令

为了成功地构建站点，需要删除该内部使用的 `replace` 指令行：`replace github.com/hbstack/theme-cards => ../`。

```sh
sed -i '/^replace/d' go.mod
```

## 安装依赖

```sh
npm ci
```

## 本地预览

```sh
npm run dev
```

## 接下来做什么？

1. 调整配置，如 `baseURL`、`giscus.*` 等。
2. 删除测试内容。
3. 阅读[文档](https://zh-hans.hbstack.dev/)。
4. 找寻更多[模块](https://hbstack.dev/modules/)。
