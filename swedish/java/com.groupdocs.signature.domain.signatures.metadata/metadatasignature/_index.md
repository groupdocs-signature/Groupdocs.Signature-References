---
title: "MetadataSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller signaturegenskaper för metadata."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Innehåller signaturegenskaper för metadata.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Anger unikt metadata namn. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Anger unikt metadata namn. |
|
|  | [getValue()](#getValue--) | Anger metadataobjekt. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Anger metadataobjekt. |
|
|  | [getType()](#getType--) | Anger metadata värdetyp. |
|
|  | [setType(int value)](#setType-int-) | Anger metadata värdetyp. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Hämtar eller anger implementering av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) gränssnittet för att koda och avkoda signaturvärdeegenskaper. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Hämtar eller anger implementering av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) gränssnittet för att koda och avkoda signaturvärdeegenskaper. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Hämta objekt från Metadata Signature Value vid deserialisering. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Hämta objekt från Metadata Signature Text vid deserialisering. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [toBoolean()](#toBoolean--) | Konverterar till boolean. |
|
|  | [toInteger()](#toInteger--) | Konverterar till heltal. |
|
|  | [toDouble()](#toDouble--) | Konverterar till Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Konverterar till Double. |
|
|  | [toSingle()](#toSingle--) | Konverterar till float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Konverterar till float. |
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
|  | [deepClone()](#deepClone--) | Klona Metadata Signature-instans. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Klona Metadata Signature-instans med angivet värde. |
|
### getName() {#getName--}
```
public final String getName()
```


Anger unikt metadata namn.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Anger unikt metadata namn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Anger metadataobjekt.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Anger metadataobjekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Anger metadata värdetyp.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Anger metadata värdetyp.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Hämtar eller anger implementering av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) gränssnittet för att koda och avkoda signaturvärdeegenskaper.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Hämtar eller anger implementering av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) gränssnittet för att koda och avkoda signaturvärdeegenskaper.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Hämta objekt från Metadata Signature Value vid deserialisering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - Instans av T-objekt


T
: Typ av objekt att deserialisera från Metadata‑värde

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Hämta objekt från Metadata Signature Text vid deserialisering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Ange anpassad implementation för datakryptering |


T
: Typ av objekt att deserialisera från Metadata‑värde
|

**Returns:**
T -
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


### toDouble() {#toDouble--}
```
public double toDouble()
```


Konverterar till Double.


**Returns:**
double - Returnerar Metadata Signature‑värdet som Double.

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

### toSingle() {#toSingle--}
```
public float toSingle()
```


Konverterar till float.


**Returns:**
float - Returnerar Metadata Signature‑värdet som float.

<br />

*** ** * ** ***

Kastar ett undantag om Metadata‑värdet inte kunde konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturens egenskapsinformation från SignatureSettings‑egenskaperna SignatureSettings.DefaultCulture().

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
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

<br />

*** ** * ** ***

Konverterar en boolesk egenskap till "True" eller "False". För en annan datatyp används standarddatformatleverantören.

<br />


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


Klona Metadata Signature-instans med angivet värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.Object | Värde för nytt klonat objekt. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

