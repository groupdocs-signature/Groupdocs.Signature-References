---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Sammlung von Metadaten-Signaturobjekten."
type: docs
weight: 13
url: /de/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Sammlung von Metadaten-Signaturobjekten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Erstellt eine Sammlung von Metadaten-Signaturen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getCount()](#getCount--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
|
|  | [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
|
|  | [contains(String name)](#contains-java.lang.String-) | Gibt true zurück, wenn eine Metadaten mit dem angegebenen Namen in der Sammlung existiert. |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | Gibt den Index einer Eigenschaft nach Namen zurück. |
|
|  | [remove(String name)](#remove-java.lang.String-) | Entfernt eine Metadaten-Signatur mit dem angegebenen Namen aus der Sammlung. |
|
|  | [removeAt(int index)](#removeAt-int-) | Entfernt eine Metadaten-Signatur am angegebenen Index. |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Fügt ein Metadaten-Signatur-Objekt zur Sammlung hinzu. |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Fügt eine Metadaten-Signatur-Sammlung hinzu. |
|
|  | [deepClone()](#deepClone--) | Klone die Klasse Metadata Signature Collection mit Metadata Signature Items. |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Erstellt eine Sammlung von Metadaten-Signaturen.


### getCount() {#getCount--}
```
public final int getCount()
```


Gibt die Anzahl der Elemente in der Sammlung zurück.


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Elemente aus der Sammlung.


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Gibt true zurück, wenn eine Metadaten mit dem angegebenen Namen in der Sammlung existiert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der nicht-groß-/kleinschreibungssensible Name der Eigenschaft. |
|

**Returns:**
boolean – Wahr, wenn die Metadaten in der Sammlung existieren; sonst falsch.

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Gibt den Index einer Eigenschaft nach Namen zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der nicht-groß-/kleinschreibungssensible Name der MetadataSignature. |
|

**Returns:**
int – Der nullbasierte Index. Negativer Wert, wenn nicht gefunden.

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Entfernt eine Metadaten-Signatur mit dem angegebenen Namen aus der Sammlung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der nicht-groß-/kleinschreibungssensible Name der Metadata Signature. |
|

**Returns:**
boolean –
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Entfernt eine Metadaten-Signatur am angegebenen Index.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Index | int | Der nullbasierte Index. |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Fügt ein Metadaten-Signatur-Objekt zur Sammlung hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Metadata-Signatur, die zur Sammlung hinzugefügt werden soll. |

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Namenswert in der gesamten bestehenden Sammlung nicht eindeutig ist.

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Fügt eine Metadaten-Signatur-Sammlung hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Sammlung von Signaturen zum Hinzufügen. |

<br />

*** ** * ** ***

Wirft eine Ausnahme, wenn der Namenswert in der gesamten bestehenden Sammlung nicht eindeutig ist.

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klone die Klasse Metadata Signature Collection mit Metadata Signature Items.


**Returns:**
java.lang.Object – Gibt eine kopierte Instanz mit geklonten Signature Items zurück.

