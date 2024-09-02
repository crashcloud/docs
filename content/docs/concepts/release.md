---
title: Release
type: docs
prev: ownership/
next: shared-model/
weight: 1003
---

> By default all of the geometry you ceate as a collaborator is temporary and cannot be edited by other users.
> By only sending temporary geometry crash does not have to block other users with your changes and does not interrupt their undo stack constantly allowing for a fluent experience.

### Why is this?

If a Geometry Object is added to Rhino it will add itself to the Undo stack.
Consider the following theoretical scenario.

- User A creates a complex loft and is trimming it with other surfaces
- User B creates a box
- User A recieves User B's Box
- If user A wants to undo a change to their work, they must also undo User B's box
