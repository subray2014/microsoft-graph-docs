---
title: "Delete alert"
description: "Deletes an alert object."
author: "preetikr"
localization_priority: Normal
ms.prod: "security"
doc_type: apiPageType
---

# Delete alert
Namespace: microsoft.graph

Deletes an [alert](../resources/alert.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|SecurityEvents.Read.All, SecurityEvents.ReadWrite.All|
|Delegated (personal Microsoft account)|Not supported|
|Application|SecurityEvents.Read.All, SecurityEvents.ReadWrite.All|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
DELETE /security/alerts/{alertId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `204 No Content` response code.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "delete_alert"
}
-->
``` http
DELETE https://graph.microsoft.com/beta/security/alerts/{alertId}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 204 No Content
```

