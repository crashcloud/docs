---
title: Crash Plugin Assembly
type: docs
prev: docs/plugins/
next: docs/plugins/changes
weight: 2001
---

The Crash Plugin must be built into an `.op` assembly. As some plugins are created for Rhino using C++ and Crash requires a separate DLL so that any Plugin can create a separate C# DLL to consume anything required. Whilst it might make sense for some plugins to include Crash inside their main plugin, I'd like to make Crash separate and available for every plugin. You should include these in your `.yak` package so that Crash can find them.

### Yak package structure

{{< filetree/container >}}
{{< filetree/folder name="Release" >}}
{{< filetree/file name="Manifest.yml" >}}

{{< filetree/folder name="net7.0" >}}
{{< filetree/file name="MyRhinoPlugin.rhp" >}}
{{< filetree/file name="MyCrashPlugin.op" >}}
{{< filetree/file name="MyPluginLib.dll" >}}
{{< /filetree/folder >}}

{{< filetree/folder name="net48" >}}
{{< filetree/file name="MyRhinoPlugin.rhp" >}}
{{< filetree/file name="MyCrashPlugin.op" >}}
{{< filetree/file name="MyPluginLib.dll" >}}
{{< /filetree/folder >}}

{{< /filetree/folder >}}
{{< /filetree/container >}}
