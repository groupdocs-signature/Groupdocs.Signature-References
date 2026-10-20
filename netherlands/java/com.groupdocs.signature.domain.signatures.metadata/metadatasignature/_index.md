---
title: "MetadataSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat ondertekenings‑eigenschappen voor metadata."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Bevat ondertekenings‑eigenschappen voor metadata.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Specificeert unieke metadata-naam. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Specificeert unieke metadata-naam. |
|
|  | [getValue()](#getValue--) | Specificeert metadata-object. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Specificeert metadata-object. |
|
|  | [getType()](#getType--) | Specificeert type van metadata-waarde. |
|
|  | [setType(int value)](#setType-int-) | Specificeert type van metadata-waarde. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Haalt of stelt implementatie van [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface in om handtekening Value-eigenschappen te coderen en decoderen. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Haalt of stelt implementatie van [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface in om handtekening Value-eigenschappen te coderen en decoderen. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Verkrijg object van Metadata Signature Value tijdens deserialisatie. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Verkrijg object van Metadata Signature Text tijdens deserialisatie. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [toBoolean()](#toBoolean--) | Converteert naar boolean. |
|
|  | [toInteger()](#toInteger--) | Converteert naar integer. |
|
|  | [toDouble()](#toDouble--) | Converteert naar Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Converteert naar Double. |
|
|  | [toSingle()](#toSingle--) | Converteert naar float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Converteert naar float. |
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
|  | [deepClone()](#deepClone--) | Kloon Metadata Signature-instantie. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Kloon Metadata Signature instantie met opgegeven waarde. |
|
### getName() {#getName--}
```
public final String getName()
```


Specificeert unieke metadata-naam.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specificeert unieke metadata-naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Specificeert metadata-object.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Specificeert metadata-object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Specificeert type van metadata-waarde.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Specificeert type van metadata-waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Haalt of stelt implementatie van [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface in om handtekening Value-eigenschappen te coderen en decoderen.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Haalt of stelt implementatie van [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface in om handtekening Value-eigenschappen te coderen en decoderen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Verkrijg object van Metadata Signature Value tijdens deserialisatie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - Instantie van T-object


T
: Type van object om te deserialiseren van Metadata-waarde

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Verkrijg object van Metadata Signature Text tijdens deserialisatie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Stel aangepaste gegevensversleutelingimplementatie in |


T
: Type object om te deserialiseren van Metadata Value
|

**Returns:**
T -
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


### toDouble() {#toDouble--}
```
public double toDouble()
```


Converteert naar Double.


**Returns:**
double - Retourneert de Metadata Signature value als Double.

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

### toSingle() {#toSingle--}
```
public float toSingle()
```


Converteert naar float.


**Returns:**
float - Retourneert de Metadata Signature value als float.

<br />

*** ** * ** ***

Gooit een uitzondering als de Metadata-waarde niet kon worden geconverteerd. Als de oorspronkelijke waarde op een string is gebaseerd, wordt de standaardcultuur‑eigenschapsinformatie gebruikt uit de SignatureSettings‑eigenschappen SignatureSettings.DefaultCulture ()

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
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

<br />

*** ** * ** ***

Converteert een boolean‑eigenschap naar "True" of "False". Voor een ander gegevenstype wordt de standaardgegevens‑formaatprovider gebruikt.

<br />


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


Kloon Metadata Signature instantie met opgegeven waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Object | Waarde voor het nieuwe gekloonde object. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

