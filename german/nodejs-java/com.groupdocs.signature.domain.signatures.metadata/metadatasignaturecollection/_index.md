---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Sammlung von Metadaten-Signaturobjekten."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
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
| [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Erstellt eine Sammlung von Metadata Signature. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Ermittelt die Anzahl der Elemente in der Sammlung. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [contains(String name)](#contains-java.lang.String-) | Gibt true zurück, wenn ein Metadata mit dem angegebenen Namen in der Sammlung existiert. |
| [indexOf(String name)](#indexOf-java.lang.String-) | Ermittelt den Index einer Eigenschaft nach Namen. |
| [remove(String name)](#remove-java.lang.String-) | Entfernt ein Metadata Signature mit dem angegebenen Namen aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein Metadata Signature am angegebenen Index. |
| [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Fügt ein Metadata Signature-Objekt zur Sammlung hinzu. |
| [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Fügt eine Metadata Signature-Sammlung hinzu. |
| [deepClone()](#deepClone--) | Klont die Klasse Metadata Signature Collection mit Metadata Signature-Elementen. |
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Erstellt eine Sammlung von Metadata Signature.

### getCount() {#getCount--}
```
public final int getCount()
```


Ermittelt die Anzahl der Elemente in der Sammlung.

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


Gibt true zurück, wenn ein Metadata mit dem angegebenen Namen in der Sammlung existiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Der nicht‑groß-/kleinschreibungsabhängige Name der Eigenschaft. |

**Returns:**
boolean - True, wenn das Metadata in der Sammlung existiert; sonst false.
### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Ermittelt den Index einer Eigenschaft nach Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Der nicht‑groß-/kleinschreibungsabhängige Name des MetadataSignature. |

**Returns:**
int - Der nullbasierte Index. Negativer Wert, wenn nicht gefunden.
### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Entfernt ein Metadata Signature mit dem angegebenen Namen aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Der nicht‑groß-/kleinschreibungsabhängige Name des Metadata Signature. |

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Entfernt ein Metadata Signature am angegebenen Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Der nullbasierte Index. |

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Fügt ein Metadata Signature-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Metadata Signature, das zur Sammlung hinzugefügt werden soll. |

--------------------

Wirft eine Ausnahme, wenn der Namenswert in der gesamten bestehenden Sammlung nicht eindeutig ist |

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Fügt eine Metadata Signature-Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Sammlung von Signaturen zum Hinzufügen. |

--------------------

Wirft eine Ausnahme, wenn der Namenswert in der gesamten bestehenden Sammlung nicht eindeutig ist |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klont die Klasse Metadata Signature Collection mit Metadata Signature-Elementen.

**Returns:**
java.lang.Object - Gibt eine kopierte Instanz mit geklonten Signature-Elementen zurück
