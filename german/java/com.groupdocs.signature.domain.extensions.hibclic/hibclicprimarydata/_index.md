---
title: "HIBCLICPrimaryData"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Klasse zum Speichern der primären Daten des HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 12
url: /de/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Klasse zum Speichern primärer HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code)-Daten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Standard ctor() |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifiziert das Datum des Kennzeichners‑Identifikationscodes. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifiziert das Datum des Kennzeichners‑Identifikationscodes. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifiziert Produkt- oder Katalognummer. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifiziert Produkt- oder Katalognummer. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifiziert die Einheit‑ID. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifiziert die Einheit‑ID. |
|
|  | [deepClone()](#deepClone--) | Liest eine Kopie dieses Objekts. |
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


Identifiziert das Datum des Kennzeichners‑Identifikationscodes. Der Kennzeichners‑Identifikationscode muss
eine 4‑stellige alphanumerische Zeichenkette sein, wobei das erste Zeichen immer alphabetisch sein muss.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Identifiziert das Datum des Kennzeichners‑Identifikationscodes. Der Kennzeichners‑Identifikationscode muss
eine 4‑stellige alphanumerische Zeichenkette sein, wobei das erste Zeichen immer alphabetisch sein muss.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Identifiziert Produkt- oder Katalognummer. Produkt- oder Katalognummer muss alphanumerisch sein
Zeichenkette mit einer Länge von bis zu 18 Zeichen.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Identifiziert Produkt- oder Katalognummer. Produkt- oder Katalognummer muss alphanumerisch sein
Zeichenkette mit einer Länge von bis zu 18 Zeichen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Identifiziert die Einheit‑ID. Die Einheit‑ID muss ein ganzzahliger Wert von 0 bis 9 sein.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Identifiziert die Einheit‑ID. Die Einheit‑ID muss ein ganzzahliger Wert von 0 bis 9 sein.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Liest eine Kopie dieses Objekts.


**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
