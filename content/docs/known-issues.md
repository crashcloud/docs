---
title: Known Issues
type: docs
prev: troubleshooting
next: concepts/
sidebar:
  open: true
toc: true
weight: 20
---

{{< callout emoji="🪲" >}}
If you find a bug, please create an issue in the repository, or post on Discourse!
{{< /callout >}}

## All Versions

- Versions of Crash and Crash.Server must match, there is no version compatibility yet
- Unsupported Elements
  - Grips
  - Groups
  - Blocks
  - Layers
  - Materials
  - Linestyles
    (I think you get the picture, Crash is fairly basic currently!)

## 1.4.0-wip (and previous)

- Crash cannot send data items over 1mb currently
  > FIX : You can fix this by modifying config in your crash.server release/build
- Unsupported Elements
  - Layers
- Hitting undo quickly after creating an item can result in it not sending
