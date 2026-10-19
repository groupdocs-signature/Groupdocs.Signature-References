---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Bild-Metadaten-Signatur-Eigenschaften."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Enthält Bild-Metadaten-Signatur-Eigenschaften.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Erstellt eine Image Metadata Signature mit Id und Wert. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getId()](#getId--) | Der Bezeichner der Image Metadata Signature. |
|
|  | [setId(int value)](#setId-int-) | Der Bezeichner der Image Metadata Signature. |
|
|  | [getSize()](#getSize--) | Nur-Lese-Wert zum Abrufen der Größe des Metadatenwerts. |
|
|  | [setSize(int value)](#setSize-int-) | Nur-Lese-Wert zum Abrufen der Größe des Metadatenwerts. |
|
|  | [getDescription()](#getDescription--) | Nur-Lese-Wert zum Abrufen der Beschreibung für die standardmäßige Image Metadata Signature. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
|  | [deepClone()](#deepClone--) | Klont die Metadaten-Signatur-Instanz. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Klont die Image Metadata Signature-Instanz mit dem angegebenen Wert. |
|
|  | [toBoolean()](#toBoolean--) | Konvertiert zu booleschem Wert. |
|
|  | [toInteger()](#toInteger--) | Konvertiert zu Ganzzahl. |
|
|  | [toLong()](#toLong--) | Konvertiert zu long. |
|
|  | [toSingle()](#toSingle--) | Konvertiert zu Float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Konvertiert zu Float. |
|
|  | [toDouble()](#toDouble--) | Konvertiert zu Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Konvertiert zu Double. |
|
|  | [toDecimal()](#toDecimal--) | Konvertiert zu Dezimal. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Konvertiert zu Dezimal. |
|
|  | [toDateTime()](#toDateTime--) | Konvertiert zu DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Konvertiert zu DateTime. |
|
|  | [toString()](#toString--) | Konvertiert zu String mit überschriebenem ToString()-Methode. |
|
|  | [toString(String format)](#toString-java.lang.String-) | Konvertiert zu String mit angegebenem Format. |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Konvertiert zu String mit angegebenem Format. |
|
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Erstellt eine Image Metadata Signature mit Id und Wert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | id | int | Eindeutiger Bezeichner des Image‑Metadata‑Signature‑Namens. Siehe Referenzen für Exif‑Tag‑Spezifikationen für mögliche ID‑Werte. |
|
|  | Wert | java.lang.Object | Metadata‑Wert |
|

### getId() {#getId--}
```
public final int getId()
```


Der Bezeichner der Image Metadata Signature.
Siehe die Klasse [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures), die eine Standard‑Signatur mit vordefiniertem Id‑Wert enthält.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Der Bezeichner der Image Metadata Signature.
Siehe die Klasse [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures), die eine Standard‑Signatur mit vordefiniertem Id‑Wert enthält.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Nur-Lese-Wert zum Abrufen der Größe des Metadatenwerts.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Nur-Lese-Wert zum Abrufen der Größe des Metadatenwerts.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Nur-Lese-Wert zum Abrufen der Beschreibung für die standardmäßige Image Metadata Signature.


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Signatur | java.lang.Object | Signaturobjekt zum Vergleich. |
|

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Signaturobjekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode


**Returns:**
int - Signatur-Hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klont die Metadaten-Signatur-Instanz.


**Returns:**
java.lang.Object - Gibt die geklonte Metadaten-Signatur-Instanz zurück

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Klont die Image Metadata Signature-Instanz mit dem angegebenen Wert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Object | Wert für das neue geklonte Objekt. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Konvertiert zu booleschem Wert.


**Returns:**
boolean – Gibt den Metadaten-Signaturwert als booleschen Wert zurück.

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden kann.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


Konvertiert zu Ganzzahl.


**Returns:**
int – Gibt den Metadaten-Signaturwert als Ganzzahl zurück.

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden kann.

<br />


### toLong() {#toLong--}
```
public final long toLong()
```


Konvertiert zu long.


**Returns:**
long - Gibt den Wert der Metadaten‑Signatur als long zurück.

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden kann.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


Konvertiert zu Float.


**Returns:**
float - Gibt den Wert der Bild‑Metadaten‑Signatur als float zurück.

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden kann. Wenn der ursprüngliche Wert auf einer Zeichenkette basiert, wird die Standardkultur‑Eigenschaftsinformation aus den SignatureSettings‑Eigenschaften SignatureSettings.DefaultCulture verwendet.

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Konvertiert zu Float.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.

<br />

|

**Returns:**
float - Gibt den Metadata Signature-Wert als float zurück.

### toDouble() {#toDouble--}
```
public double toDouble()
```


Konvertiert zu Double.


**Returns:**
double - Gibt den Wert der Bild‑Metadaten‑Signatur als Double zurück.

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden kann. Wenn der ursprüngliche Wert auf einer Zeichenkette basiert, wird die Standardkultur‑Eigenschaftsinformation aus den SignatureSettings‑Eigenschaften SignatureSettings.DefaultCulture verwendet.

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Konvertiert zu Double.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.

<br />

|

**Returns:**
double – Gibt den Metadaten-Signaturwert als Double zurück.

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Konvertiert zu Dezimal.


**Returns:**
java.math.BigDecimal - Gibt den Wert der Bild‑Metadaten‑Signatur als Dezimal zurück.

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden kann. Wenn der ursprüngliche Wert auf einer Zeichenkette basiert, wird die Standardkultur‑Eigenschaftsinformation aus den SignatureSettings‑Eigenschaften SignatureSettings.DefaultCulture verwendet.

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Konvertiert zu Dezimal.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.

<br />

|

**Returns:**
java.math.BigDecimal - Gibt den Wert der Metadaten‑Signatur als Dezimal zurück.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Konvertiert zu DateTime.


**Returns:**
java.util.Date - Gibt den Metadata Signature-Wert als DateTime zurück.

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden kann. Wenn der ursprüngliche Wert auf einer Zeichenkette basiert, wird die Standardkultur‑Eigenschaftsinformation aus den SignatureSettings‑Eigenschaften SignatureSettings.DefaultCulture verwendet.

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Konvertiert zu DateTime.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.

<br />

|

**Returns:**
java.util.Date - Gibt den Metadata Signature-Wert als DateTime zurück.

### toString() {#toString--}
```
public String toString()
```


Konvertiert zu String mit überschriebenem ToString()-Methode.


**Returns:**
java.lang.String - Gibt den Metadata Signature-Wert als String zurück.

### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Konvertiert zu String mit angegebenem Format.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | format | java.lang.String | Datenformatzeichenfolge. |

<br />

*** ** * ** ***

Konvertiert eine boolesche Eigenschaft in "True" oder "False". Die standardmäßige Kultur-Property-Info wird aus den SignatureSettings-Eigenschaften SignatureSettings.DefaultCulture verwendet.

<br />

|

**Returns:**
java.lang.String - Gibt den Metadata Signature-Wert als String zurück.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Konvertiert zu String mit angegebenem Format.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | format | java.lang.String | Datenformatzeichenfolge. |
|
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

<br />

*** ** * ** ***

Konvertiert eine boolesche Eigenschaft in "True" oder "False".

<br />

|

**Returns:**
java.lang.String - Gibt den Metadata Signature-Wert als String zurück.

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

