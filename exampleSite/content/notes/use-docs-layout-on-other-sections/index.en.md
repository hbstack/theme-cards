---
type: docs
title: "Use Docs Layout on other Sections"
description: "Guide for using the docs layout on other sections."
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
  - Notes
categories:
tags:
  - Layouts
images:
  - https://images.pexels.com/photos/1629212/pexels-photo-1629212.jpeg?auto=compress&cs=tinysrgb&w=1600
authors:
  - HB
  - HugoMods
---

## Backgrounds

The docs module/layout was applied for the `docs` section by default, it makes sense to separate the multiple digital gardens into different sections in most cases, such as docs for multiple projects, guides and notes.

## How to Use Docs Layout on other Sections?

To use the docs layout on sections other than `docs`, what you need to do is to set the `type` to `docs` in front matter.

{{< bs/config-toggle >}}
type: docs
{{< /bs/config-toggle >}}
