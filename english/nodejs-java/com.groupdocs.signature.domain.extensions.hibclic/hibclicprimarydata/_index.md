---
title: HIBCLICPrimaryData
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Class for storing HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code primary data.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Class for storing HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) primary data.
## Constructors

| Constructor | Description |
| --- | --- |
| [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Default ctor() |
## Methods

| Method | Description |
| --- | --- |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifies date of labeler identification code. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifies date of labeler identification code. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifies product or catalog number. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifies product or catalog number. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifies unit of measure ID. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifies unit of measure ID. |
| [deepClone()](#deepClone--) | Gets a copy of this object. |
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Default ctor()

### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Identifies date of labeler identification code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic.

**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Identifies date of labeler identification code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Identifies product or catalog number. Product or catalog number must be alphanumeric string up to 18 symbols length.

**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Identifies product or catalog number. Product or catalog number must be alphanumeric string up to 18 symbols length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Identifies unit of measure ID. Unit of measure ID must be integer value from 0 to 9.

**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Identifies unit of measure ID. Unit of measure ID must be integer value from 0 to 9.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Gets a copy of this object.

**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
