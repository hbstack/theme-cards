---
title: "数学排版"
date: 2023-11-26T16:36:24+08:00
draft: false
description: "本文提供了一些通过 KaTeX 进行数学排版的示例。"
noindex: false
featured: true
pinned: false
# comments: false
series:
 - 示例
categories:
 - 内容
tags:
 - 数学
 - KaTeX
images:
  - https://example-images.razonyang.com/math.webp?width=1920&height=1280
authors:
  - HB
  - HugoMods
---

## 使用 KaTeX 代码块

````markdown
```katex
f(a,b,c) = (a^2+b^2+c^2)^3
```
````

```katex
f(a,b,c) = (a^2+b^2+c^2)^3
```

## 使用 KaTeX 短代码

```markdown
{{</* katex */>}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{</* /katex */>}}
```

{{< katex >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}

## 延伸阅读

- [KaTeX 官网](https://katex.org/)
- [Hugo KaTeX 模块](https://hugomods.com/docs/content/katex/)
