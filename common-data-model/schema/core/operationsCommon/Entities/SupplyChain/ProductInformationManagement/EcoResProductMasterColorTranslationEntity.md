---
title: EcoResProductMasterColorTranslationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Product master color translations

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductMasterColorTranslationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product master color translations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DimensionTableId](#DimensionTableId)||<a href="EcoResProductMasterColorTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterColorTranslationEntity</a>|
|[ProductMasterNumber](#ProductMasterNumber)||<a href="EcoResProductMasterColorTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterColorTranslationEntity</a>|
|[ProductMasterColorId](#ProductMasterColorId)||<a href="EcoResProductMasterColorTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterColorTranslationEntity</a>|
|[LanguageId](#LanguageId)||<a href="EcoResProductMasterColorTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterColorTranslationEntity</a>|
|[TranslatedColorName](#TranslatedColorName)||<a href="EcoResProductMasterColorTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterColorTranslationEntity</a>|
|[TranslatedColorDescription](#TranslatedColorDescription)||<a href="EcoResProductMasterColorTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterColorTranslationEntity</a>|
|[Relationship_ProductMasterColorRelationshipId](#Relationship_ProductMasterColorRelationshipId)||<a href="EcoResProductMasterColorTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterColorTranslationEntity</a>|
|[BackingTable_EcoResProductMasterDimValueTranslationRelationshipId](#BackingTable_EcoResProductMasterDimValueTranslationRelationshipId)||<a href="EcoResProductMasterColorTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterColorTranslationEntity</a>|

### <a href=#DimensionTableId name="DimensionTableId">DimensionTableId</a>

First included in: ProductInformationManagement/EcoResProductMasterColorTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductMasterNumber name="ProductMasterNumber">ProductMasterNumber</a>

First included in: ProductInformationManagement/EcoResProductMasterColorTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductMasterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductMasterColorId name="ProductMasterColorId">ProductMasterColorId</a>

First included in: ProductInformationManagement/EcoResProductMasterColorTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductMasterColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProductInformationManagement/EcoResProductMasterColorTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslatedColorName name="TranslatedColorName">TranslatedColorName</a>

First included in: ProductInformationManagement/EcoResProductMasterColorTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslatedColorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslatedColorDescription name="TranslatedColorDescription">TranslatedColorDescription</a>

First included in: ProductInformationManagement/EcoResProductMasterColorTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslatedColorDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductMasterColorRelationshipId name="Relationship_ProductMasterColorRelationshipId">Relationship_ProductMasterColorRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductMasterColorTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductMasterColorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResProductMasterDimValueTranslationRelationshipId name="BackingTable_EcoResProductMasterDimValueTranslationRelationshipId">BackingTable_EcoResProductMasterDimValueTranslationRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductMasterColorTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResProductMasterDimValueTranslationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMasterDimValueTranslation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMasterDimValueTranslation.cdm.json/EcoResProductMasterDimValueTranslation</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMasterDimValueTranslation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>