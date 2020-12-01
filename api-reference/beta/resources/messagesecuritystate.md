---
title: "messageSecurityState resource type"
description: "contains definition of the message"
author: "preetikr"
localization_priority: Normal
ms.prod: "security"
doc_type: resourcePageType
---

# messageSecurityState resource type

Namespace: microsoft.graph

Contains useful more detailed information about the alert message.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|connectingIP|String|The IP Address of the source computer/client from which the alert originated.|
|deliveryAction|String|**TODO: Add Description**|
|deliveryLocation|String|**TODO: Add Description**|
|directionality|String|**TODO: Add Description**|
|internetMessageId|String|**TODO: Add Description**|
|messageFingerprint|String|**TODO: Add Description**|
|messageReceivedDateTime|DateTimeOffset|The date and time the alert message as received, represented in ISO 8601 format, and always in UTC time. This property is automatically populated when the message is logged. Read-only. Required.|
|messageSubject|String|The subject of the alert message|
|networkMessageId|String|The id of the alert message. This property is automatically assigned. Read-only. Required.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.messageSecurityState"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.messageSecurityState",
  "connectingIP": "String",
  "directionality": "String",
  "deliveryAction": "String",
  "deliveryLocation": "String",
  "internetMessageId": "String",
  "messageReceivedDateTime": "String (timestamp)",
  "messageSubject": "String",
  "messageFingerprint": "String",
  "networkMessageId": "String"
}
```

