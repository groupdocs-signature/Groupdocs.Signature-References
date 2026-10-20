---
title: "SearchResult"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Resultado de la búsqueda de firmas en el documento especificado."
type: docs
weight: 16
url: /es/java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Resultado de la búsqueda de firmas en el documento especificado.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Devuelve el tiempo de ejecución del proceso de búsqueda en milisegundos. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Devuelve el total de firmas procesadas por el proceso de búsqueda |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Devuelve el tamaño del documento de origen |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Devuelve el tamaño del documento de destino. |
|
|  | [getSucceeded()](#getSucceeded--) | Lista de firmas encontradas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista de firmas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) que fallaron el proceso de búsqueda por criterios de búsqueda. |
|
|  | [getSignatures()](#getSignatures--) | Lista de firmas detectadas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Proporciona conversión a una lista fuertemente tipada de firmas. |
|
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Devuelve el tiempo de ejecución del proceso de búsqueda en milisegundos.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Devuelve el total de firmas procesadas por el proceso de búsqueda


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Devuelve el tamaño del documento de origen


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Devuelve el tamaño del documento de destino. Para el método Search siempre devuelve 0.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lista de firmas encontradas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Esta lista siempre será igual a
Firmas
(#getSignatures.getSignatures/#setSignatures(List).setSignatures(List)) propiedad.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista de firmas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) que fallaron el proceso de búsqueda por criterios de búsqueda.
No soportado en la versión actual.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Lista de firmas detectadas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Proporciona conversión a una lista fuertemente tipada de firmas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Devuelve una lista del tipo de firma especificado.


T
 : El tipo de firmas en la lista.

### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

