# HB Cards Theme

[![Used By](https://badgen.net/github/dependents-repo/hbstack/theme-cards?label=used%20by)](https://github.com/hbstack/theme-cards/network/dependents)
![Hugo Requirements](https://img.shields.io/badge/dynamic/json?color=important&label=requirements&query=requirements&logo=hugo&style=flat-square&url=https://api.razonyang.com/v1/hugo/modules/github.com/hbstack/theme-cards)
[![License](https://badgen.net/github/license/hbstack/theme-cards)](https://github.com/hbstack/theme-cards/blob/main/LICENSE)
[![Version](https://badgen.net/github/tag/hbstack/theme-cards)](https://github.com/hbstack/theme-cards/tags)

The cards theme of [HB Framework](https://hbstack.dev/), live demo: https://theme-cards.hbstack.dev/.

## Documentation

| English | 简体中文 |
| --- | --- |
| [Install from scratch](https://theme-cards.hbstack.dev/docs/install-from-scratch/) | [从头开始安装](https://theme-cards.hbstack.dev/zh-hans/docs/install-from-scratch/) |
| [Migrate from starter theme](https://theme-cards.hbstack.dev/docs/migrate-from-starter-theme/) | [从新手模板迁移](https://theme-cards.hbstack.dev/zh-hans/docs/migrate-from-starter-theme/) |

## Screenshot

![Screenshot](https://raw.githubusercontent.com/hbstack/theme-cards/main/images/screenshot.png)

## Features

- **Fast** and **SEO** friendly: [PageSpeed Insight](https://pagespeed.web.dev/analysis?url=https://theme-cards.hbstack.dev/) scored perfect :100: in all four metrics on mobile and desktop.
- **Multi-purpose**: blog, project documentation, digital gardens, landing pages and so on.
- **Responsive**: mobile first, built on top of Bootstrap v5.3.
- :ice_cube: **Modular** and **flexible**: extend features via various modules.
- :first_quarter_moon: **Dark mode**: light, dark or auto (follow system).
- :mag: **Search**: powerful client side *fuzzy* search that allows *filtering* and *sorting* of results, as well as searching from all multilingual sites.
- **PurgeCSS**: remove unused CSS.
- :rocket: **PWA**:
  - Installable: add site to home screen.
  - Offline available: offline page and offline image.
  - Allow precaching resources, such as CSS, JS and fonts.
- **Advanced**:
  - Custom SCSS [variables](https://github.com/hbstack/theme-cards/blob/main/exampleSite/assets/hb/modules/custom/scss/variables.tmpl.scss) and [style](https://github.com/hbstack/theme-cards/blob/main/exampleSite/assets/hb/modules/custom/scss/index.scss).
  - Custom [JavaScript](https://github.com/hbstack/theme-cards/blob/main/exampleSite/assets/hb/modules/custom/js/index.ts).
  - Custom HTML markup:
    - [Before the end of `<head>`](https://github.com/hbstack/theme-cards/blob/main/exampleSite/layouts/partials/hugopress/modules/hb-custom/hooks/head-end.html)
    - [Before the end of `<body>`](https://github.com/hbstack/theme-cards/blob/main/exampleSite/layouts/partials/hugopress/modules/hb-custom/hooks/body-end.html)
    - [Custom sidebar widget](https://github.com/hbstack/theme-cards/blob/main/exampleSite/layouts/partials/hugopress/modules/hb-custom/hooks/hb-blog-sidebar.html)
- :framed_picture: **Images Processing**: process images via URL query string and fragment, such as alignment, resizing, cropping and so on, friendly to Markdown.
- :computer: **Code block panel**: expand toggle, code copy button, line number toggle and wrap toggle.
- **Menus**: supports header menus and footer menus.
- Related posts slide.
- :framed_picture: Image viewer: zoom in/out image.
- :card_index_dividers:	**Archives**: group by year and month.
- :memo: **Multiple authors**: articles can be co-authored.
- :globe_with_meridians: **Multilingual**.
- :arrow_left: **RTL**: supports Right-to-Left languages.
- :arrow_up: Back/Return to top button.
- Social links: supports header and footer social links.
- Content: supports KaTex (math), Mermaid (diagrams) and Bootstrap shortcodes.
- ...
