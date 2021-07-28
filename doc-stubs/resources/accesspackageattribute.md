---
title: "accessPackageAttribute resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackageAttribute resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|attributeDestination|[accessPackageAttributeDestination](../resources/accesspackageattributedestination.md)|**TODO: Add Description**|
|attributeName|String|**TODO: Add Description**|
|attributeSource|[accessPackageAttributeSource](../resources/accesspackageattributesource.md)|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isEditable|String|**TODO: Add Description**|
|isPersistedOnAssignmentRemoval|Boolean|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.accessPackageAttribute"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageAttribute",
  "id": "String (identifier)",
  "attributeName": "String",
  "attributeSource": {
    "@odata.type": "microsoft.graph.accessPackageAttributeSource"
  },
  "attributeDestination": {
    "@odata.type": "microsoft.graph.accessPackageAttributeDestination"
  },
  "isEditable": "String",
  "isPersistedOnAssignmentRemoval": "Boolean"
}
```

