---
title: "HIBCLICPrimaryData"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Klasse zum Speichern der primären Daten des HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
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
| [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Standard ctor() |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifiziert das Datum des Labeler-Identifikationscodes. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifiziert das Datum des Labeler-Identifikationscodes. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifiziert Produkt- oder Katalognummer. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifiziert Produkt- oder Katalognummer. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifiziert die ID der Maßeinheit. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifiziert die ID der Maßeinheit. |
| [deepClone()](#deepClone--) | Liefert eine Kopie dieses Objekts. |
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


Identifiziert das Datum des Labeler-Identifikationscodes. Der Labeler-Identifikationscode muss eine alphanumerische Zeichenkette aus 4 Symbolen sein, wobei das erste Zeichen immer alphabetisch ist.

**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Identifiziert das Datum des Labeler-Identifikationscodes. Der Labeler-Identifikationscode muss eine alphanumerische Zeichenkette aus 4 Symbolen sein, wobei das erste Zeichen immer alphabetisch ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Identifiziert Produkt- oder Katalognummer. Produkt- oder Katalognummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein.

**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Identifiziert Produkt- oder Katalognummer. Produkt- oder Katalognummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Identifiziert die ID der Maßeinheit. Die ID der Maßeinheit muss ein ganzzahliger Wert von 0 bis 9 sein.

**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Identifiziert die ID der Maßeinheit. Die ID der Maßeinheit muss ein ganzzahliger Wert von 0 bis 9 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Liefert eine Kopie dieses Objekts.

**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
