---
title: "BaseSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Beschrijft de basisklasse voor handtekeningen."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Beschrijft de basisklasse voor handtekeningen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | Specificeert het type handtekening. |
|
|  | [getPageNumber()](#getPageNumber--) | Specificeert de pagina waarop de handtekening is gevonden. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Specificeert de pagina waarop de handtekening is gevonden. |
|
|  | [getSignatureId()](#getSignatureId--) | Unieke handtekeningidentificatie om de handtekening in het document te wijzigen via Update- of Delete-methoden. |
|
|  | [isSignature()](#isSignature--) | Haal op of stel de vlag in om aan te geven of dit component een Signature of documentinhoud is. |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | Haal op of stel de vlag in om aan te geven of dit component een Signature of documentinhoud is. |
|
|  | [getDeleted()](#getDeleted--) | Haal op of stel de vlag in om aan te geven of deze handtekening uit het document is verwijderd. |
|
|  | [getCreatedOn()](#getCreatedOn--) | Haal op of stel de creatiedatum van de handtekening in. |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Haal op of stel de creatiedatum van de handtekening in. |
|
|  | [getModifiedOn()](#getModifiedOn--) | Haal op of stel de wijzigingsdatum van de handtekening in. |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Haal op of stel de wijzigingsdatum van de handtekening in. |
|
|  | [getTop()](#getTop--) | Bepaalt de bovenste positie van de handtekening. |
|
|  | [setTop(int value)](#setTop-int-) | Bepaalt de bovenste positie van de handtekening. |
|
|  | [getLeft()](#getLeft--) | Bepaalt de linkse positie van de handtekening. |
|
|  | [setLeft(int value)](#setLeft-int-) | Bepaalt de linkse positie van de handtekening. |
|
|  | [getWidth()](#getWidth--) | Bepaalt de breedte van de handtekening. |
|
|  | [setWidth(int value)](#setWidth-int-) | Bepaalt de breedte van de handtekening. |
|
|  | [getHeight()](#getHeight--) | Bepaalt de hoogte van de handtekening. |
|
|  | [setHeight(int value)](#setHeight-int-) | Bepaalt de hoogte van de handtekening. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Bepaalt het type handtekening. Een digitale handtekening zal deze eigenschap hebben.


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Specificeert de pagina waarop de handtekening is gevonden.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Specificeert de pagina waarop de handtekening is gevonden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Unieke handtekeningidentificatie om de handtekening in het document te wijzigen via Update- of Delete-methoden.
Deze eigenschap wordt automatisch ingesteld nadat de Sign- of Search-methode is aangeroepen.
Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren.


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Haal op of stel de vlag in om aan te geven of dit component een Signature of documentinhoud is.
Deze eigenschap wordt gebruikt met de Update-methode om het element als handtekening (true) of als documentelement (false) in te stellen.


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Haal op of stel de vlag in om aan te geven of dit component een Signature of documentinhoud is.
Deze eigenschap wordt gebruikt met de Update-methode om het element als handtekening (true) of als documentelement (false) in te stellen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Haal op of stel de vlag in om aan te geven of deze handtekening uit het document is verwijderd.
Deze eigenschap wordt alleen gebruikt voor logrecords van de documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden.


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Haal op of stel de creatiedatum van de handtekening in.


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Haal op of stel de creatiedatum van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Haal op of stel de wijzigingsdatum van de handtekening in.


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Haal op of stel de wijzigingsdatum van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Bepaalt de bovenste positie van de handtekening.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Bepaalt de bovenste positie van de handtekening.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Bepaalt de linkse positie van de handtekening.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Bepaalt de linkse positie van de handtekening.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Bepaalt de breedte van de handtekening.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Bepaalt de breedte van de handtekening.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Bepaalt de hoogte van de handtekening.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Bepaalt de hoogte van de handtekening.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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
