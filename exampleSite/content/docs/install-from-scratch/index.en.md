---
title: "Install From Scratch"
description: "Getting started from scratch with HB cards theme to build your fast, responsive and modular static websites."
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
  - Docs
categories:
tags:
  - Installation
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

We offers an example site for getting started with this theme.

## Requirements

- Go
- Hugo extended version
- Node.js `16` or later

Read more on [prerequisites](https://hbstack.dev/docs/getting-started/prerequisites/).

## Clone the Repository

```sh
git clone --depth 1 https://github.com/hbstack/theme-cards
```

## Copy the Example Site

```sh
cp -r theme-cards/exampleSite mysite
```

## Change Working Directory

```sh
cd mysite
```

## Tweak `go.mod`

### Replace Module Path

The module path is the identifier of your site, which typically is your repo URL, take `github.com/user/repo` as an example.

```sh
sed -i '1s/.*/module github.com\/user\/repo/' go.mod
```

### Delete the `replace` Directive

To build the site successfully, you'll need to delete the internal used `replace` directive: `replace github.com/hbstack/theme-cards => ../`.

```sh
sed -i '/^replace/d' go.mod
```

## Install Dependencies

```sh
npm ci
```

## Preview Locally

```sh
npm run dev
```

## What's Next?

1. Tweak Configurations, such as `baseURL`, `giscus.*` and so on.
2. Remove testing content.
3. Read the [documentations](https://hbstack.dev/).
4. Find more [modules](https://hbstack.dev/modules/).
