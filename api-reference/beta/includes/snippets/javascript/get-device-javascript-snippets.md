---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let device = await client.api('/devices/{id}')
	.version('beta')
	.get();

```