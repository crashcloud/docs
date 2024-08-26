---
title: Changes
type: docs
prev: docs/advanced/assembly
next: docs/advanced/events
weight: 2002
---

# Change Definition

The Change Definition describes how the changes are drawn, if at all, how they are categorised and what actions can be taken with the changes. In this definition you can also create custom Tables inside of the Crash Document to store information.

{{< cards >}}
{{< card link="https://github.com/crashcloud/Crash/blob/main/src/Crash.Handlers/Plugins/IChangeDefinition.cs" title="IChangeDefinition.cs" icon="code" >}}
{{< /cards >}}

# Change Create Action

Change Create Actions define the circumstances in which a Change is created. This could be a Box being moved, deleted, selected, or even a completely unique event in your Plugin!

{{< cards >}}
{{< card link="https://github.com/crashcloud/Crash/blob/main/src/Crash.Handlers/Plugins/IChangeCreateAction.cs" title="IChangeCreateAction.cs" icon="code" >}}
{{< /cards >}}

# Change Receive Action

Change Receive Actions define how changes get created locally when a Change is received from the server that matches the description of the Change Definition.

{{< cards >}}
{{< card link="https://github.com/crashcloud/Crash/blob/main/src/Crash.Handlers/Plugins/IChangeRecieveAction.cs" title="IChangeRecieveAction.cs" icon="code" >}}
{{< /cards >}}
