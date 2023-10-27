---
type: docs
title: "于其他板块使用文档布局"
description: "在其他板块使用文档布局的指南。"
# linkTitle:
date: 2023-11-02T11:47:31+08:00
draft: false
noindex: false
featured: true
pinned: false
nav_weight: 1000
nav_icon:
  vendor: bootstrap
  name: columns
  color: green
series:
  - 笔记
categories:
tags:
  - 布局
images:
  - https://images.pexels.com/photos/1629212/pexels-photo-1629212.jpeg?auto=compress&cs=tinysrgb&w=1600
authors:
  - HB
  - HugoMods
---

## 背景

默认情况下，文档布局应用于 `docs` 板块，在大多数情况下，将多个数字花园分割成不同的板块是合理的，例如多个项目的文档、指南和笔记。

## 如何在其他部分使用文档布局？

要在 `docs` 以外的板块使用文档布局，你需要做的是在前言中将 `type` 设置为 `docs`。

{{< bs/config-toggle >}}
type: docs
{{< /bs/config-toggle >}}
