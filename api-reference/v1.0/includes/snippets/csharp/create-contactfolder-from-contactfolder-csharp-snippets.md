---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var contactFolder = new ContactFolder
{
	DisplayName = "displayName-value"
};

await graphClient.Me.ContactFolders["{contactFolder-id}"].ChildFolders
	.Request()
	.AddAsync(contactFolder);

```