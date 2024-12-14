---
title: "Migrate from HB Starter Theme"
description: "This guide shows how to migrate to the HB cards theme from the HB starter theme."
# linkTitle:
date: 2023-12-01T11:47:31+08:00
draft: false
noindex: false
featured: true
pinned: false
nav_weight: 2
nav_icon:
  vendor: bootstrap
  name: arrow-clockwise
  className: text-primary
series:
  - Docs
categories:
tags:
  - Migration
images:
  - https://example-images.razonyang.com/speed.webp?width=1920&height=1280
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

You can migrate to cards theme from the [starter theme](https://github.com/hbstack/theme) effortlessly within two steps.

## Import the Cards Theme Module

{{< bs/alert danger >}}
{{< markdownify >}}
You'll have to put the module `github.com/hbstack/theme-cards` on the ___top___, to make sure that the cards theme gets higher priority.
{{< /markdownify >}}
{{< /bs/alert >}}

{{< bs/config-toggle "hugo" >}}
module:
  imports:
    - path: github.com/hbstack/theme-cards
{{< /bs/config-toggle >}}

## Tweak Parameters

To make the carousel take up a whole row on the homepage, you'll need to tweak the position of pinned posts.

{{< bs/config-toggle "params" >}}
hb:
  blog:
    home:
      pinned_posts_position: list
{{< /bs/config-toggle >}}
