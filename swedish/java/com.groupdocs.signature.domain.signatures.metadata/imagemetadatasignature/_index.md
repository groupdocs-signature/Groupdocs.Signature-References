---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller signaturegenskaper för bildmetadata."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Innehåller signaturegenskaper för bildmetadata.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Skapar Image Metadata Signature med Id och värde |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getId()](#getId--) | Identifieraren för Image Metadata signature. |
|
|  | [setId(int value)](#setId-int-) | Identifieraren för Image Metadata signature. |
|
|  | [getSize()](#getSize--) | Skrivskyddat värde för att få storleken på Metadata‑värdet. |
|
|  | [setSize(int value)](#setSize-int-) | Skrivskyddat värde för att få storleken på Metadata‑värdet. |
|
|  | [getDescription()](#getDescription--) | Skrivskyddat värde för att få beskrivning för standard Image Metadata signature |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona Metadata Signature-instans. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Klona Image Metadata Signature‑instans med angivet värde. |
|
|  | [toBoolean()](#toBoolean--) | Konverterar till boolean. |
|
|  | [toInteger()](#toInteger--) | Konverterar till heltal. |
|
|  | [toLong()](#toLong--) | Konverterar till long. |
|
|  | [toSingle()](#toSingle--) | Konverterar till float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Konverterar till float. |
|
|  | [toDouble()](#toDouble--) | Konverterar till Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Konverterar till Double. |
|
|  | [toDecimal()](#toDecimal--) | Konverterar till Decimal. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Konverterar till Decimal. |
|
|  | [toDateTime()](#toDateTime--) | Konverterar till DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Konverterar till DateTime. |
|
|  | [toString()](#toString--) | Konverterar till String med överskriven ToString()-metod |
|
|  | [toString(String format)](#toString-java.lang.String-) | Konverterar till String med angivet format |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Konverterar till String med angivet format |
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


Skapar Image Metadata Signature med Id och värde


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | id | int | Unik identifierare för namn på bildmetadata‑signatur. Se referenser för Exif‑tagspecifikationer för möjliga id‑värden |
|
|  | värde | java.lang.Object | Metadata‑värde |
|

### getId() {#getId--}
```
public final int getId()
```


Identifieraren för Image Metadata signature.
Se [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) klass som innehåller standard Signature med fördefinierat Id‑värde.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Identifieraren för Image Metadata signature.
Se [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) klass som innehåller standard Signature med fördefinierat Id‑värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Skrivskyddat värde för att få storleken på Metadata‑värdet.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Skrivskyddat värde för att få storleken på Metadata‑värdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Skrivskyddat värde för att få beskrivning för standard Image Metadata signature


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Skriver över Equals-metoden för att jämföra signaturens egenskaper


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatur | java.lang.Object | Signaturobjekt att jämföra med. |
|

**Returns:**
boolean - Returnerar true om det överförda signaturobjektet har samma typ och alla dess egenskaper är lika med egenskaperna i denna instans.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter GetHashCode‑metoden.


**Returns:**
int - Signaturens hashkod

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klona Metadata Signature-instans.


**Returns:**
java.lang.Object - Returnerar klonad Metadata Signature-instans

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Klona Image Metadata Signature‑instans med angivet värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.Object | Värde för nytt klonat objekt. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Konverterar till boolean.


**Returns:**
boolean - Returnerar Metadata‑signaturvärdet som boolean.

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


Konverterar till heltal.


**Returns:**
int - Returnerar Metadata Signature‑värdet som heltal.

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras.

<br />


### toLong() {#toLong--}
```
public final long toLong()
```


Konverterar till long.


**Returns:**
long - Returnerar Metadata Signature‑värdet som long.

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


Konverterar till float.


**Returns:**
float - Returnerar Image Metadata Signature‑värdet som float.

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturens egenskapsinformation från SignatureSettings‑egenskaperna SignatureSettings.DefaultCulture.

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Konverterar till float.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | leverantör | java.util.Locale | Formatera dataleverantör att använda med datakonverteringsoperationer. |

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras

<br />

|

**Returns:**
float - Returnerar Metadata Signature‑värdet som float.

### toDouble() {#toDouble--}
```
public double toDouble()
```


Konverterar till Double.


**Returns:**
double - Returnerar Image Metadata Signature‑värdet som Double.

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturens egenskapsinformation från SignatureSettings‑egenskaperna SignatureSettings.DefaultCulture.

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Konverterar till Double.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | leverantör | java.util.Locale | Formatera dataleverantör att använda med datakonverteringsoperationer. |

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras

<br />

|

**Returns:**
double - Returnerar Metadata Signature‑värdet som Double.

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Konverterar till Decimal.


**Returns:**
java.math.BigDecimal - Returnerar Image Metadata Signature‑värdet som Decimal.

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturens egenskapsinformation från SignatureSettings‑egenskaperna SignatureSettings.DefaultCulture.

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Konverterar till Decimal.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | leverantör | java.util.Locale | Formatera dataleverantör att använda med datakonverteringsoperationer. |

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras

<br />

|

**Returns:**
java.math.BigDecimal - Returnerar Metadata Signature‑värdet som Decimal.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Konverterar till DateTime.


**Returns:**
java.util.Date - Returnerar Metadata Signature‑värdet som DateTime.

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturens egenskapsinformation från SignatureSettings‑egenskaperna SignatureSettings.DefaultCulture.

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Konverterar till DateTime.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | leverantör | java.util.Locale | Formatera dataleverantör att använda med datakonverteringsoperationer. |

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras

<br />

|

**Returns:**
java.util.Date - Returnerar Metadata Signature‑värdet som DateTime.

### toString() {#toString--}
```
public String toString()
```


Konverterar till String med överskriven ToString()-metod


**Returns:**
java.lang.String - Returnerar Metadata Signature‑värdet som String.

### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Konverterar till String med angivet format


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | format | java.lang.String | Dataformatsträng. |

<br />

*** ** * ** ***

Konverterar en boolesk egenskap till "True" eller "False". Standardkulturens egenskapsinformation används från SignatureSettings‑egenskaperna SignatureSettings.DefaultCulture.

<br />

|

**Returns:**
java.lang.String - Returnerar Metadata Signature‑värdet som String.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Konverterar till String med angivet format


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | format | java.lang.String | Dataformatsträng. |
|
|  | leverantör | java.util.Locale | Formatera dataleverantör att använda med datakonverteringsoperationer. |

<br />

*** ** * ** ***

Konverterar en boolesk egenskap till "True" eller "False".

<br />

|

**Returns:**
java.lang.String - Returnerar Metadata Signature‑värdet som String.

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

