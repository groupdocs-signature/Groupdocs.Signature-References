---
title: "BaseSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Beschreibt die Basisklasse für Signaturen."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Beschreibt die Basisklasse für Signaturen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | Gibt den Typ der Signatur an. |
|
|  | [getPageNumber()](#getPageNumber--) | Gibt die Seite an, auf der die Signatur gefunden wurde. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Gibt die Seite an, auf der die Signatur gefunden wurde. |
|
|  | [getSignatureId()](#getSignatureId--) | Eindeutiger Signatur-Identifikator, um die Signatur im Dokument über die Update- oder Delete-Methoden zu ändern. |
|
|  | [isSignature()](#isSignature--) | Lese- oder Schreib-Flag, das angibt, ob diese Komponente eine Signatur oder Dokumenteninhalt ist. |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | Lese- oder Schreib-Flag, das angibt, ob diese Komponente eine Signatur oder Dokumenteninhalt ist. |
|
|  | [getDeleted()](#getDeleted--) | Lese- oder Schreib-Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. |
|
|  | [getCreatedOn()](#getCreatedOn--) | Lese- oder Schreib-Datum der Signaturerstellung. |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Lese- oder Schreib-Datum der Signaturerstellung. |
|
|  | [getModifiedOn()](#getModifiedOn--) | Lese- oder Schreib-Datum der Signaturänderung. |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Lese- oder Schreib-Datum der Signaturänderung. |
|
|  | [getTop()](#getTop--) | Gibt die obere Position der Signatur an. |
|
|  | [setTop(int value)](#setTop-int-) | Gibt die obere Position der Signatur an. |
|
|  | [getLeft()](#getLeft--) | Gibt die linke Position der Signatur an. |
|
|  | [setLeft(int value)](#setLeft-int-) | Gibt die linke Position der Signatur an. |
|
|  | [getWidth()](#getWidth--) | Gibt die Breite der Signatur an. |
|
|  | [setWidth(int value)](#setWidth-int-) | Gibt die Breite der Signatur an. |
|
|  | [getHeight()](#getHeight--) | Gibt die Höhe der Signatur an. |
|
|  | [setHeight(int value)](#setHeight-int-) | Gibt die Höhe der Signatur an. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Gibt den Typ der Signatur an. Digitale Signaturen besitzen diese Eigenschaft.


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Gibt die Seite an, auf der die Signatur gefunden wurde.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Gibt die Seite an, auf der die Signatur gefunden wurde.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Eindeutiger Signatur-Identifikator, um die Signatur im Dokument über die Update- oder Delete-Methoden zu ändern.
Diese Eigenschaft wird automatisch gesetzt, nachdem die Sign- oder Search-Methode aufgerufen wurde.
Wenn diese Eigenschaft zuvor gespeichert wurde, kann sie manuell gesetzt werden, um die Signatur zu manipulieren.


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Lese- oder Schreib-Flag, das angibt, ob diese Komponente eine Signatur oder Dokumenteninhalt ist.
Diese Eigenschaft wird mit der Update-Methode verwendet, um das Element als Signatur (true) oder Dokumentenelement (false) festzulegen.


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Lese- oder Schreib-Flag, das angibt, ob diese Komponente eine Signatur oder Dokumenteninhalt ist.
Diese Eigenschaft wird mit der Update-Methode verwendet, um das Element als Signatur (true) oder Dokumentenelement (false) festzulegen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Lese- oder Schreib-Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde.
Diese Eigenschaft wird nur für Dokumenten-Historienprotokolle verwendet, um die Liste gelöschter Signaturen zu führen.


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Lese- oder Schreib-Datum der Signaturerstellung.


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Lese- oder Schreib-Datum der Signaturerstellung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Lese- oder Schreib-Datum der Signaturänderung.


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Lese- oder Schreib-Datum der Signaturänderung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Gibt die obere Position der Signatur an.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Gibt die obere Position der Signatur an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Gibt die linke Position der Signatur an.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Gibt die linke Position der Signatur an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gibt die Breite der Signatur an.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Gibt die Breite der Signatur an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gibt die Höhe der Signatur an.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Gibt die Höhe der Signatur an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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
