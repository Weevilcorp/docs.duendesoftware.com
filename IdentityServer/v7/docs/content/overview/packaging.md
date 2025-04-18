---
title: "Packaging and Builds"
date: 2020-09-10T08:22:12+02:00
weight: 40
---

### Product
The licensed and supported libraries can be accessed via Nuget:

* [Duende IdentityServer](https://www.nuget.org/packages/Duende.IdentityServer)
* [Duende IdentityServer EntityFramework Integration](https://www.nuget.org/packages/Duende.IdentityServer.EntityFramework)
* [Duende IdentityServer ASP.NET Identity Integration](https://www.nuget.org/packages/Duende.IdentityServer.AspNetIdentity)

### UI
Duende IdentityServer does not contain any UI, because this is always custom to the project. 
We still provide you with the [IdentityServer Quickstart UI](https://github.com/DuendeSoftware/products/tree/main/identity-server/templates/src/UI)
as a starting point for your modifications.

### Templates
Contains templates for the dotnet CLI.

* NuGet [package](https://www.nuget.org/packages/Duende.Templates)
* [source code](https://github.com/DuendeSoftware/products/tree/main/templates)

You can install the templates using the following command:

```
dotnet new -i Duende.Templates
```

{{% notice note %}}
You may have a previous version of Duende templates (*Duende.IdentityServer.Templates*) installed on your machine. 
Please uninstall the template package and install the latest version.
{{% /notice %}}

### Source Code
You can find the Duende IdentityServer source code on [GitHub][source].

[source]: https://github.com/DuendeSoftware/products/tree/main/templates
