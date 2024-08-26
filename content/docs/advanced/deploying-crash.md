---
title: Deploying Crash
type: docs
prev: docs/folder/
next: docs/advanced/
toc: true
---

{{< callout emoji="⚠️" >}}
Crash does not offer an authentication system (… yet …), if someone knows the URL they can join!
{{< /callout >}}

## Deploy Crash

### Choose a Crash Release

{{< tabs items="Exe,Docker" >}}

{{< tab >}}**Exe**:

{{< callout emoji="⚠️" >}}
crash.server is only released for Windows currently. If you need a linux build you can build it from source easily.
{{< /callout >}}

- Download a copy of Crash.Server from [Releases](https://github.com/crashcloud/crash.server/releases)
- Extract the `.zip`
- Open terminal and cd into `crash.server`
- Run the `crash.server.exe` executable
  - running `.\crash.server.exe --help` will provide useful information that is more up to date than I can keep here
  - By default crash will run on `http://0.0.0.0:8080 or http://localhost:8080`

{{< /tab >}}

{{< tab >}}**Docker**:

```bash
docker pull crashserver/crash.server

docker run -p 8080:8080 crashserver/crash.server
```

{{< /tab >}}

{{< /tabs >}}

## Hosting

{{< tabs items="Locally,Azure" >}}

{{< tab >}}**Locally**:

- Follow steps above.

{{< /tab >}}

{{< tab >}}**Azure**:

Crash can be hosted easily using Azure and creating a Web App.

{{< cards >}}
{{< card link="https://www.youtube.com/watch?v=_LNOg8kU4CE" title="Creating an Azure Web App" icon="book-open" >}}
{{< /cards >}}

{{< /tab >}}

{{< /tabs >}}

## Validation

Visit the url of the Crash server on your Computer, if you can see this page, you can join the server!

![Crash Splash](crash-splash.png)
