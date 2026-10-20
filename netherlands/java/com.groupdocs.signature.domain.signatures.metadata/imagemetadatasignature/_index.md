---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat ondertekenings‑eigenschappen voor afbeeldingsmetadata."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Bevat ondertekenings‑eigenschappen voor afbeeldingsmetadata.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Maakt Image Metadata Signature met Id en waarde |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getId()](#getId--) | De identifier van Image Metadata signature. |
|
|  | [setId(int value)](#setId-int-) | De identifier van Image Metadata signature. |
|
|  | [getSize()](#getSize--) | Alleen-lezen waarde om de grootte van Metadata-waarde te krijgen |
|
|  | [setSize(int value)](#setSize-int-) | Alleen-lezen waarde om de grootte van Metadata-waarde te krijgen |
|
|  | [getDescription()](#getDescription--) | Alleen-lezen waarde om de beschrijving voor standaard Image Metadata signature te krijgen |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon Metadata Signature-instantie. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Kloon Image Metadata Signature instantie met opgegeven waarde. |
|
|  | [toBoolean()](#toBoolean--) | Converteert naar boolean. |
|
|  | [toInteger()](#toInteger--) | Converteert naar integer. |
|
|  | [toLong()](#toLong--) | Converteert naar long. |
|
|  | [toSingle()](#toSingle--) | Converteert naar float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Converteert naar float. |
|
|  | [toDouble()](#toDouble--) | Converteert naar Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Converteert naar Double. |
|
|  | [toDecimal()](#toDecimal--) | Converteert naar Decimal. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Converteert naar Decimal. |
|
|  | [toDateTime()](#toDateTime--) | Converteert naar DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Converteert naar DateTime. |
|
|  | [toString()](#toString--) | Converteert naar String met overschreven ToString() methode |
|
|  | [toString(String format)](#toString-java.lang.String-) | Converteert naar String met opgegeven formaat |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Converteert naar String met opgegeven formaat |
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


Maakt Image Metadata Signature met Id en waarde


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | id | int | Unieke identifier van de Image Metadata Signature-naam. Zie referenties voor Exif-tag specificaties voor mogelijke id-waarden |
|
|  | waarde | java.lang.Object | Metadatawaarde |
|

### getId() {#getId--}
```
public final int getId()
```


De identifier van Image Metadata signature.
Zie [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) klasse die standaard Signature bevat met vooraf gedefinieerde Id-waarde.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


De identifier van Image Metadata signature.
Zie [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) klasse die standaard Signature bevat met vooraf gedefinieerde Id-waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Alleen-lezen waarde om de grootte van Metadata-waarde te krijgen


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Alleen-lezen waarde om de grootte van Metadata-waarde te krijgen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Alleen-lezen waarde om de beschrijving voor standaard Image Metadata signature te krijgen


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | handtekening | java.lang.Object | Handtekeningobject om mee te vergelijken. |
|

**Returns:**
boolean - Retourneert true als het meegegeven handtekeningobject hetzelfde type heeft en al zijn eigenschappen gelijk zijn aan de eigenschappen van deze instantie.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Overschrijft de GetHashCode‑methode


**Returns:**
int - Handtekening hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Kloon Metadata Signature-instantie.


**Returns:**
java.lang.Object - Retourneert een gekloonde Metadata Signature-instantie

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Kloon Image Metadata Signature instantie met opgegeven waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Object | Waarde voor het nieuwe gekloonde object. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Converteert naar boolean.


**Returns:**
boolean - Retourneert de Metadata signature value als boolean.

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


Converteert naar integer.


**Returns:**
int - Retourneert de Metadata Signature value als integer.

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd.

<br />


### toLong() {#toLong--}
```
public final long toLong()
```


Converteert naar long.


**Returns:**
long - Retourneert de Metadata Signature-waarde als long.

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


Converteert naar float.


**Returns:**
float - Retourneert de Image Metadata Signature-waarde als float.

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd. Als de oorspronkelijke waarde op een string is gebaseerd, wordt de standaardcultuur‑eigenschapsinformatie gebruikt uit de SignatureSettings‑eigenschappen SignatureSettings.DefaultCulture

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Converteert naar float.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | provider | java.util.Locale | Format data provider om te gebruiken bij gegevensconversie‑bewerkingen. |

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd

<br />

|

**Returns:**
float - Retourneert de Metadata Signature value als float.

### toDouble() {#toDouble--}
```
public double toDouble()
```


Converteert naar Double.


**Returns:**
double - Retourneert de Image Metadata Signature-waarde als Double.

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd. Als de oorspronkelijke waarde op een string is gebaseerd, wordt de standaardcultuur‑eigenschapsinformatie gebruikt uit de SignatureSettings‑eigenschappen SignatureSettings.DefaultCulture

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Converteert naar Double.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | provider | java.util.Locale | Format data provider om te gebruiken bij gegevensconversie‑bewerkingen. |

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd

<br />

|

**Returns:**
double - Retourneert de Metadata Signature value als Double.

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Converteert naar Decimal.


**Returns:**
java.math.BigDecimal - Retourneert de Image Metadata Signature-waarde als Decimal.

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd. Als de oorspronkelijke waarde op een string is gebaseerd, wordt de standaardcultuur‑eigenschapsinformatie gebruikt uit de SignatureSettings‑eigenschappen SignatureSettings.DefaultCulture

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Converteert naar Decimal.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | provider | java.util.Locale | Format data provider om te gebruiken bij gegevensconversie‑bewerkingen. |

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd

<br />

|

**Returns:**
java.math.BigDecimal - Retourneert de Metadata Signature-waarde als Decimal.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Converteert naar DateTime.


**Returns:**
java.util.Date - Retourneert de Metadata Signature value als DateTime.

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd. Als de oorspronkelijke waarde op een string is gebaseerd, wordt de standaardcultuur‑eigenschapsinformatie gebruikt uit de SignatureSettings‑eigenschappen SignatureSettings.DefaultCulture

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Converteert naar DateTime.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | provider | java.util.Locale | Format data provider om te gebruiken bij gegevensconversie‑bewerkingen. |

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd

<br />

|

**Returns:**
java.util.Date - Retourneert de Metadata Signature value als DateTime.

### toString() {#toString--}
```
public String toString()
```


Converteert naar String met overschreven ToString() methode


**Returns:**
java.lang.String - Retourneert de Metadata Signature value als String.

### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Converteert naar String met opgegeven formaat


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | format | java.lang.String | Gegevensformaat‑string. |

<br />

*** ** * ** ***

Converteert een boolean‑eigenschap naar "True" of "False". Standaardcultuur‑eigenschapsinformatie wordt gebruikt uit de SignatureSettings‑eigenschappen SignatureSettings.DefaultCulture

<br />

|

**Returns:**
java.lang.String - Retourneert de Metadata Signature value als String.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Converteert naar String met opgegeven formaat


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | format | java.lang.String | Gegevensformaat‑string. |
|
|  | provider | java.util.Locale | Format data provider om te gebruiken bij gegevensconversie‑bewerkingen. |

<br />

*** ** * ** ***

Converteert een boolean‑eigenschap naar "True" of "False".

<br />

|

**Returns:**
java.lang.String - Retourneert de Metadata Signature value als String.

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

