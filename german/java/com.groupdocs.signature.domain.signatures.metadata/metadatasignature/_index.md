---
title: "MetadataSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Metadaten-Signatur-Eigenschaften."
type: docs
weight: 12
url: /de/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Enthält Metadaten-Signatur-Eigenschaften.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Gibt einen eindeutigen Metadaten-Namen an. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Gibt einen eindeutigen Metadaten-Namen an. |
|
|  | [getValue()](#getValue--) | Gibt das Metadaten-Objekt an. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Gibt das Metadaten-Objekt an. |
|
|  | [getType()](#getType--) | Gibt den Metadaten-Werttyp an. |
|
|  | [setType(int value)](#setType-int-) | Gibt den Metadaten-Werttyp an. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces, um Signaturwert-Eigenschaften zu kodieren und zu dekodieren. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces, um Signaturwert-Eigenschaften zu kodieren und zu dekodieren. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Erhalte das Objekt aus dem Metadaten-Signaturwert nach Deserialisierung. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Erhalte das Objekt aus dem Metadaten-Signaturtext nach Deserialisierung. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
|  | [toBoolean()](#toBoolean--) | Konvertiert zu booleschem Wert. |
|
|  | [toInteger()](#toInteger--) | Konvertiert zu Ganzzahl. |
|
|  | [toDouble()](#toDouble--) | Konvertiert zu Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Konvertiert zu Double. |
|
|  | [toSingle()](#toSingle--) | Konvertiert zu Float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Konvertiert zu Float. |
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
|  | [deepClone()](#deepClone--) | Klont die Metadaten-Signatur-Instanz. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Klont die Metadaten-Signatur-Instanz mit dem angegebenen Wert. |
|
### getName() {#getName--}
```
public final String getName()
```


Gibt einen eindeutigen Metadaten-Namen an.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gibt einen eindeutigen Metadaten-Namen an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Gibt das Metadaten-Objekt an.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Gibt das Metadaten-Objekt an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Gibt den Metadaten-Werttyp an.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Gibt den Metadaten-Werttyp an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces, um Signaturwert-Eigenschaften zu kodieren und zu dekodieren.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces, um Signaturwert-Eigenschaften zu kodieren und zu dekodieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Erhalte das Objekt aus dem Metadaten-Signaturwert nach Deserialisierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - Instanz des T-Objekts


T
: Typ des Objekts, das aus dem Metadatenwert deserialisiert werden soll

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Erhalte das Objekt aus dem Metadaten-Signaturtext nach Deserialisierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Benutzerdefinierte Datenverschlüsselungsimplementierung festlegen |


T
: Typ des Objekts, das aus dem Metadatenwert deserialisiert werden soll
|

**Returns:**
T -
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


### toDouble() {#toDouble--}
```
public double toDouble()
```


Konvertiert zu Double.


**Returns:**
double – Gibt den Metadaten-Signaturwert als Double zurück.

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

### toSingle() {#toSingle--}
```
public float toSingle()
```


Konvertiert zu Float.


**Returns:**
float - Gibt den Metadata Signature-Wert als float zurück.

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte. Wenn der ursprüngliche Wert zeichenkettenbasiert ist, wird die standardmäßige Kultur-Property-Info aus den SignatureSettings-Eigenschaften SignatureSettings.DefaultCulture () verwendet.

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
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

<br />

*** ** * ** ***

Konvertiert eine boolesche Eigenschaft in "True" oder "False". Für andere Datentypen wird der standardmäßige Datenformatanbieter verwendet.

<br />


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


Klont die Metadaten-Signatur-Instanz mit dem angegebenen Wert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Object | Wert für das neue geklonte Objekt. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

