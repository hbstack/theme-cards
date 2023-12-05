---
title: "Diagrams and Charts"
date: 2023-11-26T16:36:24+08:00
draft: false
description: "This article offers some examples about using Mermaid for diagramming and charting."
noindex: false
featured: true
pinned: false
# comments: false
series:
 - Examples
categories:
 - Content
tags:
 - Diagrams
 - Charts
 - Mermaid
images:
  - https://example-images.razonyang.com/flowchart.webp?width=1920&height=1280
authors:
  - HB
  - HugoMods
---

## Using Mermaid Code Block

````markdown
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
````

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Using Mermaid Shortcode

```markdown
{{</* mermaid */>}}
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
{{</* /mermaid */>}}
```

{{< mermaid >}}
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
{{< /mermaid >}}

## Further Reading

- [Mermaid official site](https://mermaid.js.org/)
- [Hugo Mermaid module](https://hugomods.com/docs/content/mermaid/)
