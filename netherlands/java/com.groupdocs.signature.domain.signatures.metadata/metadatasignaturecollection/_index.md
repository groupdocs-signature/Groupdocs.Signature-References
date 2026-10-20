---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Collectie van ondertekeningsobjecten voor metadata."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Collectie van ondertekeningsobjecten voor metadata.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Maakt een collectie van Metadata-handtekeningen aan. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCount()](#getCount--) | Haalt het aantal items in de collectie op. |
|
|  | [clear()](#clear--) | Verwijdert alle items uit de collectie. |
|
|  | [contains(String name)](#contains-java.lang.String-) | Retourneert true als een Metadata met de opgegeven naam bestaat in de collectie. |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | Haalt de index van een eigenschap op basis van de naam. |
|
|  | [remove(String name)](#remove-java.lang.String-) | Verwijdert een Metadata Signature met de opgegeven naam uit de collectie. |
|
|  | [removeAt(int index)](#removeAt-int-) | Verwijdert een Metadata Signature op de opgegeven index. |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Voeg Metadata Signature-object toe aan de collectie. |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Voeg Metadata Signature-collectie toe. |
|
|  | [deepClone()](#deepClone--) | Kloon de Metadata Signature Collection-klasse met Metadata Signature-items. |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Maakt een collectie van Metadata-handtekeningen aan.


### getCount() {#getCount--}
```
public final int getCount()
```


Haalt het aantal items in de collectie op.


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle items uit de collectie.


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Retourneert true als een Metadata met de opgegeven naam bestaat in de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | De hoofdletterongevoelige naam van de eigenschap. |
|

**Returns:**
boolean - True als de Metadata bestaat in de collectie; anders false.

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Haalt de index van een eigenschap op basis van de naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | De hoofdletterongevoelige naam van de MetadataSignature. |
|

**Returns:**
int - De nulgebaseerde index. Negatieve waarde als niet gevonden.

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Verwijdert een Metadata Signature met de opgegeven naam uit de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | De hoofdletterongevoelige naam van de Metadata Signature. |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Verwijdert een Metadata Signature op de opgegeven index.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | index | int | De nulgebaseerde index. |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Voeg Metadata Signature-object toe aan de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Metadata signature die aan de collectie moet worden toegevoegd. |

<br />

*** ** * ** ***

Gooit een uitzondering als de naamwaarde niet uniek is in de volledige bestaande collectie

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Voeg Metadata Signature-collectie toe.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Collectie van handtekeningen om toe te voegen. |

<br />

*** ** * ** ***

Gooit een uitzondering als de naamwaarde niet uniek is in de volledige bestaande collectie

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Kloon de Metadata Signature Collection-klasse met Metadata Signature-items.


**Returns:**
java.lang.Object - Retourneert een gekopieerde instantie met gekloonde Signature Items

