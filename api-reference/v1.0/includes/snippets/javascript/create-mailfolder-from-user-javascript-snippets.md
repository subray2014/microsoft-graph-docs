---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const mailFolder = {
  displayName: 'Clutter'
};

await client.api('/me/mailFolders')
	.post(mailFolder);

```