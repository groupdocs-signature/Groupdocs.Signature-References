---
title: "HIBCLICPrimaryData"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Klasse voor het opslaan van primaire gegevens van de HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Klasse voor het opslaan van HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) primaire gegevens.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Standaard ctor() |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identificeert datum van labeler identification code. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identificeert datum van labeler identification code. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identificeert product- of catalogusnummer. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identificeert product- of catalogusnummer. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identificeert eenheid-van-meet-ID. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identificeert eenheid-van-meet-ID. |
|
|  | [deepClone()](#deepClone--) | Krijgt een kopie van dit object. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Standaard ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Identificeert datum van labeler identification code. Labeler identification code moet
een alfanumerieke tekenreeks van 4 symbolen zijn, waarbij het eerste teken altijd alfabetisch is.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Identificeert datum van labeler identification code. Labeler identification code moet
een alfanumerieke tekenreeks van 4 symbolen zijn, waarbij het eerste teken altijd alfabetisch is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Identificeert product- of catalogusnummer. Product- of catalogusnummer moet alfanumeriek zijn
tekenreeks tot 18 symbolen lang.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Identificeert product- of catalogusnummer. Product- of catalogusnummer moet alfanumeriek zijn
tekenreeks tot 18 symbolen lang.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Identificeert eenheid-van-meet-ID. Eenheid-van-meet-ID moet een geheel getal zijn van 0 tot 9.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Identificeert eenheid-van-meet-ID. Eenheid-van-meet-ID moet een geheel getal zijn van 0 tot 9.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Krijgt een kopie van dit object.


**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
