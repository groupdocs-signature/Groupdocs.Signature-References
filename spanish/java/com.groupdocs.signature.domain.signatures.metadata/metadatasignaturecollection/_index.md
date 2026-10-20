---
title: "MetadataSignatureCollection"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Colección de objetos de firma de metadatos."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Colección de objetos de firma de metadatos.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Crea una colección de Metadata signature. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCount()](#getCount--) | Obtiene el número de elementos en la colección. |
|
|  | [clear()](#clear--) | Elimina todos los elementos de la colección. |
|
|  | [contains(String name)](#contains-java.lang.String-) | Devuelve true si existe un Metadata con el nombre especificado en la colección. |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | Obtiene el índice de una propiedad por nombre. |
|
|  | [remove(String name)](#remove-java.lang.String-) | Elimina una Metadata Signature con el nombre especificado de la colección. |
|
|  | [removeAt(int index)](#removeAt-int-) | Elimina una Metadata Signature en el índice especificado. |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Añade un objeto Metadata Signature a la colección. |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Añade una colección de Metadata Signature. |
|
|  | [deepClone()](#deepClone--) | Clase Clone Metadata Signature Collection con Metadata Signature Items. |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Crea una colección de Metadata signature.


### getCount() {#getCount--}
```
public final int getCount()
```


Obtiene el número de elementos en la colección.


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Elimina todos los elementos de la colección.


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Devuelve true si existe un Metadata con el nombre especificado en la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | El nombre sin distinción de mayúsculas y minúsculas de la propiedad. |
|

**Returns:**
boolean - Verdadero si el Metadata existe en la colección; falso en caso contrario.

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Obtiene el índice de una propiedad por nombre.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | El nombre sin distinción de mayúsculas y minúsculas del MetadataSignature. |
|

**Returns:**
int - El índice basado en cero. Valor negativo si no se encuentra.

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Elimina una Metadata Signature con el nombre especificado de la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | El nombre sin distinción de mayúsculas y minúsculas de la Metadata Signature. |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Elimina una Metadata Signature en el índice especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | índice | int | El índice basado en cero. |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Añade un objeto Metadata Signature a la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Firma de metadatos que se añadirá a la colección. |

<br />

*** ** * ** ***

Lanza una excepción si el valor del nombre no es único en toda la colección existente

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Añade una colección de Metadata Signature.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Colección de firmas para añadir. |

<br />

*** ** * ** ***

Lanza una excepción si el valor del nombre no es único en toda la colección existente

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clase Clone Metadata Signature Collection con Metadata Signature Items.


**Returns:**
java.lang.Object - Devuelve una instancia copiada con Signature Items clonados

