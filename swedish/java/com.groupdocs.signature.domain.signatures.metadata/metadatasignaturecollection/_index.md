---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Samling av metadata‑signaturobjekt."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Samling av metadata‑signaturobjekt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Skapar en samling av Metadata‑signatur. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCount()](#getCount--) | Hämtar antalet objekt i samlingen. |
|
|  | [clear()](#clear--) | Tar bort alla objekt från samlingen. |
|
|  | [contains(String name)](#contains-java.lang.String-) | Returnerar true om en Metadata med det angivna namnet finns i samlingen. |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | Hämtar indexet för en egenskap efter namn. |
|
|  | [remove(String name)](#remove-java.lang.String-) | Tar bort en Metadata‑signatur med det angivna namnet från samlingen. |
|
|  | [removeAt(int index)](#removeAt-int-) | Tar bort en Metadata‑signatur på det angivna indexet. |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Lägg till Metadata‑signaturobjekt i samlingen. |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Lägg till Metadata‑signatursamling. |
|
|  | [deepClone()](#deepClone--) | Klona Metadata‑signatursamling‑klassen med Metadata‑signaturobjekt. |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Skapar en samling av Metadata‑signatur.


### getCount() {#getCount--}
```
public final int getCount()
```


Hämtar antalet objekt i samlingen.


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Tar bort alla objekt från samlingen.


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Returnerar true om en Metadata med det angivna namnet finns i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Det skiftlägesokänsliga namnet på egenskapen. |
|

**Returns:**
boolean - True om Metadata finns i samlingen; false annars.

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Hämtar indexet för en egenskap efter namn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Det skiftlägesokänsliga namnet på MetadataSignature. |
|

**Returns:**
int - Nollbaserat index. Negativt värde om inte hittat.

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Tar bort en Metadata‑signatur med det angivna namnet från samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Det skiftlägesokänsliga namnet på Metadata‑signaturen. |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Tar bort en Metadata‑signatur på det angivna indexet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | index | int | Det nollbaserade indexet. |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Lägg till Metadata‑signaturobjekt i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Metadata‑signatur som ska läggas till i samlingen. |

<br />

*** ** * ** ***

Kastar ett undantag om namnvärdet inte är unikt i hela befintliga samlingen

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Lägg till Metadata‑signatursamling.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Samling av signaturer att lägga till. |

<br />

*** ** * ** ***

Kastar ett undantag om namnvärdet inte är unikt i hela befintliga samlingen

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klona Metadata‑signatursamling‑klassen med Metadata‑signaturobjekt.


**Returns:**
java.lang.Object - Returnerar en kopierad instans med klonade signaturobjekt

