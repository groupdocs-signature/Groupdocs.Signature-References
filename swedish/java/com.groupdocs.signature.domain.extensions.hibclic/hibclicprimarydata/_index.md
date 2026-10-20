---
title: "HIBCLICPrimaryData"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Klass för lagring av HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code primärdata."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Klass för lagring av primär HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code)-data.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Standard ctor() |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifierar datum för etikettens identifieringskod. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifierar datum för etikettens identifieringskod. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifierar produkt- eller katalognummer. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifierar produkt- eller katalognummer. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifierar enhetsmått-ID. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifierar enhetsmått-ID. |
|
|  | [deepClone()](#deepClone--) | Hämtar en kopia av detta objekt. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Standard ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Identifierar datum för etikettens identifieringskod. Etikettens identifieringskod måste
vara en alfanumerisk sträng med 4 tecken, där det första tecknet alltid är alfabetiskt.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Identifierar datum för etikettens identifieringskod. Etikettens identifieringskod måste
vara en alfanumerisk sträng med 4 tecken, där det första tecknet alltid är alfabetiskt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Identifierar produkt- eller katalognummer. Produkt- eller katalognummer måste vara alfanumeriskt
sträng med upp till 18 tecken.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Identifierar produkt- eller katalognummer. Produkt- eller katalognummer måste vara alfanumeriskt
sträng med upp till 18 tecken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Identifierar enhetsmått-ID. Enhetsmått-ID måste vara ett heltalsvärde från 0 till 9.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Identifierar enhetsmått-ID. Enhetsmått-ID måste vara ett heltalsvärde från 0 till 9.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Hämtar en kopia av detta objekt.


**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
