---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

InputStream stream = graphClient.print().printers("{printerId}").jobs("{printJobId}").documents("{printDocumentId}").content()
	.buildRequest()
	.get();

```