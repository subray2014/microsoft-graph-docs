---
title: "investigationSecurityState resource type"
description: "contains useful information about the name and status of the investigation"
author: "preetikr"
localization_priority: Normal
ms.prod: "security"
doc_type: resourcePageType
---

# investigationSecurityState resource type

Namespace: microsoft.graph

Contains definition of the investigation type as defined by the investigator.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|name|String|The name of the investiation as logged by the investigator.|
|status|String|The status of the investigation as logged by the investigator.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.investigationSecurityState"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.investigationSecurityState",
  "name": "String",
  "status": "String"
}
```

