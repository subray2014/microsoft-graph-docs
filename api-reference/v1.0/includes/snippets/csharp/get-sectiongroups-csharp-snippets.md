---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var sectionGroups = await graphClient.Me.Onenote.SectionGroups["{sectionGroup-id}"].SectionGroups
	.Request()
	.GetAsync();

```