---
title: "BaseSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Beskriver basklass för signaturer."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Beskriver basklass för signaturer.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | Anger signaturens typ. |
|
|  | [getPageNumber()](#getPageNumber--) | Anger sidan som signaturen hittades på. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Anger sidan som signaturen hittades på. |
|
|  | [getSignatureId()](#getSignatureId--) | Unik signaturidentifierare för att ändra signaturen i dokumentet via Update- eller Delete-metoder. |
|
|  | [isSignature()](#isSignature--) | Hämta eller ange flagga för att indikera om denna komponent är en signatur eller dokumentinnehåll. |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | Hämta eller ange flagga för att indikera om denna komponent är en signatur eller dokumentinnehåll. |
|
|  | [getDeleted()](#getDeleted--) | Hämta eller ange flagga för att indikera om denna signatur har raderats från dokumentet. |
|
|  | [getCreatedOn()](#getCreatedOn--) | Hämta eller ange signaturens skapelsedatum. |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Hämta eller ange signaturens skapelsedatum. |
|
|  | [getModifiedOn()](#getModifiedOn--) | Hämta eller ange signaturens ändringsdatum. |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Hämta eller ange signaturens ändringsdatum. |
|
|  | [getTop()](#getTop--) | Anger signaturens övre position. |
|
|  | [setTop(int value)](#setTop-int-) | Anger signaturens övre position. |
|
|  | [getLeft()](#getLeft--) | Anger signaturens vänstra position. |
|
|  | [setLeft(int value)](#setLeft-int-) | Anger signaturens vänstra position. |
|
|  | [getWidth()](#getWidth--) | Anger signaturens bredd. |
|
|  | [setWidth(int value)](#setWidth-int-) | Anger signaturens bredd. |
|
|  | [getHeight()](#getHeight--) | Anger signaturens höjd. |
|
|  | [setHeight(int value)](#setHeight-int-) | Anger signaturens höjd. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Anger signaturens typ. Digital signatur kommer att ha denna egenskap.


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Anger sidan som signaturen hittades på.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Anger sidan som signaturen hittades på.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Unik signaturidentifierare för att ändra signaturen i dokumentet via Update- eller Delete-metoder.
Denna egenskap kommer att sättas automatiskt efter att Sign- eller Search-metoden har anropats.
Om denna egenskap sparades tidigare kan den sättas manuellt för att manipulera signaturen.


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Hämta eller ange flagga för att indikera om denna komponent är en signatur eller dokumentinnehåll.
Denna egenskap används med Update-metoden för att ange elementet som signatur (true) eller dokumentslement (false).


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Hämta eller ange flagga för att indikera om denna komponent är en signatur eller dokumentinnehåll.
Denna egenskap används med Update-metoden för att ange elementet som signatur (true) eller dokumentslement (false).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Hämta eller ange flagga för att indikera om denna signatur har raderats från dokumentet.
Denna egenskap används endast för dokumenthistorikloggar för att behålla listan över raderade signaturer.


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Hämta eller ange signaturens skapelsedatum.


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Hämta eller ange signaturens skapelsedatum.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Hämta eller ange signaturens ändringsdatum.


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Hämta eller ange signaturens ändringsdatum.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Anger signaturens övre position.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Anger signaturens övre position.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Anger signaturens vänstra position.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Anger signaturens vänstra position.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Anger signaturens bredd.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Anger signaturens bredd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Anger signaturens höjd.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Anger signaturens höjd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
