---
title: "Diagrams and Charts"
date: 2023-11-26T16:36:24+08:00
draft: true
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
  - https://images.pexels.com/photos/1181311/pexels-photo-1181311.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1
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
