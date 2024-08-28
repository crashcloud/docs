---
title: Crash.Server Options
type: docs
prev: docs/advanced/deploying-crash
next: docs/advanced/
toc: true
weight: 3001
---

### URLs

The address of the Crash Server, including port. By Default Crash uses `https://0.0.0.0:8080`.

### Database Path

You can choose where crash stores its database, and can even use it to switch between databases.
By default crash creates the database in the User Application Data under "crash" and databases are named with the crash version as versions are not currently cross compatible.

### Reset

{{< callout type="warning" >}}
This option WILL destroy your database. DO NOT use this option without backing up important data.
{{< /callout >}}

Deletes your database and starts the server from scratch. Very useful in Debug.
