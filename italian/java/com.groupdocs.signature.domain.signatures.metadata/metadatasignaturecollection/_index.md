---
title: "MetadataSignatureCollection"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Raccolta di oggetti firma dei metadati."
type: docs
weight: 13
url: /it/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Raccolta di oggetti firma dei metadati.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Crea una collezione di firme Metadata. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCount()](#getCount--) | Ottiene il numero di elementi nella collezione. |
|
|  | [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
|
|  | [contains(String name)](#contains-java.lang.String-) | Restituisce true se un Metadata con il nome specificato esiste nella collezione. |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | Ottiene l'indice di una proprietà per nome. |
|
|  | [remove(String name)](#remove-java.lang.String-) | Rimuove una Metadata Signature con il nome specificato dalla collezione. |
|
|  | [removeAt(int index)](#removeAt-int-) | Rimuove una Metadata Signature all'indice specificato. |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Aggiungi l'oggetto Metadata Signature alla collezione. |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Aggiungi la collezione Metadata Signature. |
|
|  | [deepClone()](#deepClone--) | Clona la classe Metadata Signature Collection con gli elementi Metadata Signature. |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Crea una collezione di firme Metadata.


### getCount() {#getCount--}
```
public final int getCount()
```


Ottiene il numero di elementi nella collezione.


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti gli elementi dalla collezione.


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Restituisce true se un Metadata con il nome specificato esiste nella collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Il nome della proprietà, senza distinzione tra maiuscole e minuscole. |
|

**Returns:**
boolean - True se il Metadata esiste nella collezione; false altrimenti.

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Ottiene l'indice di una proprietà per nome.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Il nome del MetadataSignature, senza distinzione tra maiuscole e minuscole. |
|

**Returns:**
int - L'indice basato su zero. Valore negativo se non trovato.

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Rimuove una Metadata Signature con il nome specificato dalla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Il nome della Metadata Signature, senza distinzione tra maiuscole e minuscole. |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Rimuove una Metadata Signature all'indice specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | indice | int | L'indice basato su zero. |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Aggiungi l'oggetto Metadata Signature alla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Firma Metadata da aggiungere alla collezione. |

<br />

*** ** * ** ***

Lancia un'eccezione se il valore del nome non è unico nell'intera collezione esistente

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Aggiungi la collezione Metadata Signature.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Collezione di firme da aggiungere. |

<br />

*** ** * ** ***

Lancia un'eccezione se il valore del nome non è unico nell'intera collezione esistente

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona la classe Metadata Signature Collection con gli elementi Metadata Signature.


**Returns:**
java.lang.Object - Restituisce un'istanza copiata con gli elementi Signature clonati

