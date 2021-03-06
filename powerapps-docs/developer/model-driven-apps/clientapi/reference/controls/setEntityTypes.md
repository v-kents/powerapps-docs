---
title: "setEntityTypes (Client API reference) in model-driven apps| MicrosoftDocs"
ms.date: 10/31/2018
ms.service: "crm-online"
ms.topic: "reference"
applies_to: "Dynamics 365 (online)"
ms.assetid: 93154168-1e9f-4849-b4bb-be8804f86f81
author: "KumarVivek"
ms.author: "kvivek"
manager: "amyla"
search.audienceType: 
  - developer
search.app: 
  - PowerApps
  - D365CE
---
# setEntityTypes (Client API reference)



Sets the types of entities allowed in the lookup control.

## Control types supported

Lookup control

## Syntax

`formContext.getControl(arg).setEntityTypes([entityLogicalNames]);`

## Parameter

|Name|Type|Required|Description|
|--|--|--|--|
|entityLogicalNames|Array of String|Yes|Specify the logical name of the entities allowed in the lookup control.|

### Related topics

[getEntityTypes](getEntityTypes.md)

 


