---
title: KanbanRuleEvent - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Kanban event rules

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/KanbanRuleEvent.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[KanbanRuleEvent/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Kanban event rules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[BOMLineReservationMethod](#BOMLineReservationMethod)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[CancelUnusedEventsOnSourceReqReg](#CancelUnusedEventsOnSourceReqReg)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[DependentPeggedRequirementStatus](#DependentPeggedRequirementStatus)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[InventoryReservationPolicy](#InventoryReservationPolicy)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[KanbanLineEvent](#KanbanLineEvent)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[MinimumEventQuantity](#MinimumEventQuantity)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[ParentRecId](#ParentRecId)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[ProdBOMLineEvent](#ProdBOMLineEvent)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[SalesLineEvent](#SalesLineEvent)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[SalesLineReservationMethod](#SalesLineReservationMethod)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[SourceRequirementReservation](#SourceRequirementReservation)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[StockReplenishmentEvent](#StockReplenishmentEvent)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|
|[Relationship_ParentRelationshipId](#Relationship_ParentRelationshipId)||<a href="KanbanRuleEvent.md" target="_blank">Main/KanbanRuleEvent</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[KanbanRuleEvent/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BOMLineReservationMethod name="BOMLineReservationMethod">BOMLineReservationMethod</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMLineReservationMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CancelUnusedEventsOnSourceReqReg name="CancelUnusedEventsOnSourceReqReg">CancelUnusedEventsOnSourceReqReg</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delete unused event kanbans</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelUnusedEventsOnSourceReqReg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delete unused event kanbans</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DependentPeggedRequirementStatus name="DependentPeggedRequirementStatus">DependentPeggedRequirementStatus</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DependentPeggedRequirementStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventoryReservationPolicy name="InventoryReservationPolicy">InventoryReservationPolicy</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryReservationPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#KanbanLineEvent name="KanbanLineEvent">KanbanLineEvent</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KanbanLineEvent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MinimumEventQuantity name="MinimumEventQuantity">MinimumEventQuantity</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum event quantity</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumEventQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum event quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ParentRecId name="ParentRecId">ParentRecId</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProdBOMLineEvent name="ProdBOMLineEvent">ProdBOMLineEvent</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdBOMLineEvent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesLineEvent name="SalesLineEvent">SalesLineEvent</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineEvent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesLineReservationMethod name="SalesLineReservationMethod">SalesLineReservationMethod</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineReservationMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SourceRequirementReservation name="SourceRequirementReservation">SourceRequirementReservation</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source requirement reservation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRequirementReservation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source requirement reservation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StockReplenishmentEvent name="StockReplenishmentEvent">StockReplenishmentEvent</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StockReplenishmentEvent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_ParentRelationshipId name="Relationship_ParentRelationshipId">Relationship_ParentRelationshipId</a>

First included in: Main/KanbanRuleEvent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ParentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="KanbanRuleVariable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/KanbanRuleVariable.cdm.json/KanbanRuleVariable</a></td><td><a href="KanbanRuleVariable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>