---
title: "provisionedPlan resource type"
description: "The **provisionedPlans** property of the user entity and the organization entity is a collection of **provisionedPlan**."
localization_priority: Normal
---

# provisionedPlan resource type

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

The **provisionedPlans** property of the [user](user.md) entity and the [organization](organization.md) entity is a collection of **provisionedPlan**.


## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|capabilityStatus|String|For example, “Enabled”.|
|provisioningStatus|String|For example, “Success”.|
|service|String|The name of the service; for example, “AccessControlS2S”|

## JSON representation

Here is a JSON representation of the resource

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.provisionedplan"
}-->

```json
{
  "capabilityStatus": "string",
  "provisioningStatus": "string",
  "service": "string"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "provisionedPlan resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
