---
title: "alertDetection resource type"
description: "contains information abou the alert detection type"
author: "preetikr"
localization_priority: Normal
ms.prod: "*security"
doc_type: resourcePageType
---

# alertDetection resource type

Namespace: microsoft.graph

Contains critical information about the alert detection type.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|detectionType|String|The alert type. Can be information only or warning.|
|method|String|The method of alert detection. |
|name|String|The name of the alert.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.alertDetection"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.alertDetection",
  "detectionType": "String",
  "method": "String",
  "name": "String"
}
```

