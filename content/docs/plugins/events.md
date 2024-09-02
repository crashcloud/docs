---
title: Events
type: docs
prev: plugins/changes
weight: 2003
---

If you do want to subscribe to custom events and let crash know, you MUST forward the event to `crashDoc.Dispatcher.NotifyServerAsync`. It is recommended, if you can, to create your own custom event args as this will make it easier for you to capture that change in your custom `ChangeCreateAction`. DO NOT subscribe to the default Rhino Events. These are already captured by Crash. If Crash is missing a Rhino Event you would like subscribed to, please open a PR and add it. If you have your own plugin and own events, you should forward those to the Dispatcher yourself.
