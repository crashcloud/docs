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

{{< cards >}}
{{< card link="(https://github.com/crashcloud/Crash/issues/new/choose)" title="Open an Issue on GitHub" icon="github" >}}
{{< card link="https://discourse.mcneel.com/new-topic?title=issue%20with%20crash&body=please%20help&category=plug-ins/multi-user" title="Create a topic on Discourse" icon="plus" >}}
{{< /cards >}}

## All Versions

- Versions of Crash and Crash.Server must match, there is no version compatibility yet
- Unsupported Elements
  - Grips
  - Groups
  - Blocks
  - Materials
  - Linestyles
    (I think you get the picture, Crash is fairly basic currently!)

## 1.4.0-wip

- Crash cannot send data items over 1mb currently
  > FIX : You can fix this by modifying config in your crash.server release/build
- Unsupported Elements
  - Layers
- Hitting undo quickly after creating an item can result in it not sending

## 1.3.0 (and previous)

Do not use old Crash Versions
