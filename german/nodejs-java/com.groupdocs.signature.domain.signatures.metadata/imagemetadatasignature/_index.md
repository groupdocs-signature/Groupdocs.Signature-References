---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Eigenschaften der Bild‑Metadaten‑Signatur."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Enthält Eigenschaften der Bild‑Metadaten‑Signatur.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Erstellt eine Bild-Metadaten-Signatur mit Id und Wert |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getId()](#getId--) | Der Bezeichner der Bild-Metadaten-Signatur. |
| [setId(int value)](#setId-int-) | Der Bezeichner der Bild-Metadaten-Signatur. |
| [getSize()](#getSize--) | Nur-Lese-Wert, um die Größe des Metadatenwerts zu erhalten |
| [setSize(int value)](#setSize-int-) | Nur-Lese-Wert, um die Größe des Metadatenwerts zu erhalten |
| [getDescription()](#getDescription--) | Nur-Lese-Wert, um die Beschreibung für die Standard-Bild-Metadaten-Signatur zu erhalten |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die Metadaten-Signatur-Instanz. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Klont Bild-Metadaten-Signatur-Instanz mit dem angegebenen Wert. |
| [toBoolean()](#toBoolean--) | Konvertiert zu booleschem Wert. |
| [toInteger()](#toInteger--) | Konvertiert zu Ganzzahl. |
| [toLong()](#toLong--) | Konvertiert zu long. |
| [toSingle()](#toSingle--) | Konvertiert zu Float. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Konvertiert zu Float. |
| [toDouble()](#toDouble--) | Konvertiert zu Double. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Konvertiert zu Double. |
| [toDecimal()](#toDecimal--) | Konvertiert zu Decimal. |
| [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Konvertiert zu Decimal. |
| [toDateTime()](#toDateTime--) | Konvertiert zu DateTime. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Konvertiert zu DateTime. |
| [toString()](#toString--) | Konvertiert zu String mit überschriebenem ToString()-Methode |
| [toString(String format)](#toString-java.lang.String-) | Konvertiert zu String mit angegebenem Format |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Konvertiert zu String mit angegebenem Format |
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


Erstellt eine Bild-Metadaten-Signatur mit Id und Wert

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ID | int | Eindeutiger Bezeichner des Bild-Metadaten-Signaturnamens. Siehe Referenzen für Exif-Tag-Spezifikationen für mögliche ID-Werte |
| Wert | java.lang.Object | Metadatenwert |

### getId() {#getId--}
```
public final int getId()
```


Der Bezeichner der Bild-Metadaten-Signatur. Siehe [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) Klasse, die die Standard‑Signatur mit vordefiniertem Id‑Wert enthält.

**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Der Bezeichner der Bild-Metadaten-Signatur. Siehe [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) Klasse, die die Standard‑Signatur mit vordefiniertem Id‑Wert enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Nur-Lese-Wert, um die Größe des Metadatenwerts zu erhalten

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Nur-Lese-Wert, um die Größe des Metadatenwerts zu erhalten

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Nur-Lese-Wert, um die Beschreibung für die Standard-Bild-Metadaten-Signatur zu erhalten

**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Signatur | java.lang.Object | Signatur-Objekt zum Vergleichen. |

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Signatur-Objekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.
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
java.lang.Object - Gibt eine geklonte Metadata Signature-Instanz zurück
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Klont Bild-Metadaten-Signatur-Instanz mit dem angegebenen Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object | Wert für das neue geklonte Objekt. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Konvertiert zu booleschem Wert.

**Returns:**
boolean - Gibt den Metadaten-Signaturwert als booleschen Wert zurück.

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.
### toInteger() {#toInteger--}
```
public int toInteger()
```


Konvertiert zu Ganzzahl.

**Returns:**
int - Gibt den Metadaten-Signaturwert als Ganzzahl zurück.

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.
### toLong() {#toLong--}
```
public final long toLong()
```


Konvertiert zu long.

**Returns:**
long – Gibt den Metadaten‑Signaturwert als long zurück.

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.
### toSingle() {#toSingle--}
```
public final float toSingle()
```


Konvertiert zu Float.

**Returns:**
float – Gibt den Bild-Metadaten‑Signaturwert als float zurück.

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte. Wenn der ursprüngliche Wert stringbasiert ist, wird die Standardeinstellung für die Kultur aus den Eigenschaften von SignatureSettings verwendet: SignatureSettings.DefaultCulture.
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Konvertiert zu Float.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte |

**Returns:**
float - Gibt den Metadaten-Signaturwert als float zurück.
### toDouble() {#toDouble--}
```
public double toDouble()
```


Konvertiert zu Double.

**Returns:**
double – Gibt den Bild-Metadaten‑Signaturwert als Double zurück.

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte. Wenn der ursprüngliche Wert stringbasiert ist, wird die Standardeinstellung für die Kultur aus den Eigenschaften von SignatureSettings verwendet: SignatureSettings.DefaultCulture.
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Konvertiert zu Double.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte |

**Returns:**
double - Gibt den Metadaten-Signaturwert als Double zurück.
### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Konvertiert zu Decimal.

**Returns:**
java.math.BigDecimal – Gibt den Bild-Metadaten‑Signaturwert als Decimal zurück.

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte. Wenn der ursprüngliche Wert stringbasiert ist, wird die Standardeinstellung für die Kultur aus den Eigenschaften von SignatureSettings verwendet: SignatureSettings.DefaultCulture.
### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Konvertiert zu Decimal.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte |

**Returns:**
java.math.BigDecimal – Gibt den Metadaten‑Signaturwert als Decimal zurück.
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Konvertiert zu DateTime.

**Returns:**
java.util.Date - Gibt den Metadaten-Signaturwert als DateTime zurück.

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte. Wenn der ursprüngliche Wert stringbasiert ist, wird die Standardeinstellung für die Kultur aus den Eigenschaften von SignatureSettings verwendet: SignatureSettings.DefaultCulture.
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Konvertiert zu DateTime.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

--------------------

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte |

**Returns:**
java.util.Date - Gibt den Metadaten-Signaturwert als DateTime zurück.
### toString() {#toString--}
```
public String toString()
```


Konvertiert zu String mit überschriebenem ToString()-Methode

**Returns:**
java.lang.String - Gibt den Metadaten-Signaturwert als String zurück.
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Konvertiert zu String mit angegebenem Format

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Format | java.lang.String | Datenformatzeichenfolge. |

--------------------

Konvertiert eine boolesche Eigenschaft in "True" oder "False". Die Standardeinstellung für die Kultur wird aus den Eigenschaften von SignatureSettings verwendet: SignatureSettings.DefaultCulture |

**Returns:**
java.lang.String - Gibt den Metadaten-Signaturwert als String zurück.
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Konvertiert zu String mit angegebenem Format

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Format | java.lang.String | Datenformatzeichenfolge. |
|  | Anbieter | java.util.Locale | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

--------------------

Konvertiert eine boolesche Eigenschaft in "True" oder "False". |

**Returns:**
java.lang.String - Gibt den Metadaten-Signaturwert als String zurück.
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

