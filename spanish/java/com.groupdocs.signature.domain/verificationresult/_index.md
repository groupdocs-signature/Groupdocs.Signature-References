---
title: "VerificationResult"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Instancia para mantener los resultados del proceso de verificación."
type: docs
weight: 20
url: /es/java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Instancia para mantener los resultados del proceso de verificación.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Devuelve el tiempo de ejecución del proceso en milisegundos. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Devuelve el total de firmas procesadas |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Devuelve el tamaño del documento de origen en bytes |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Devuelve el tamaño del documento de destino. |
|
|  | [getSucceeded()](#getSucceeded--) | Lista de firmas verificadas con éxito [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista de firmas que fallaron en el proceso de verificación. |
|
|  | [isValid()](#isValid--) | Devuelve true si el proceso de verificación fue exitoso, de lo contrario false. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Devuelve true si el proceso de verificación fue exitoso, de lo contrario false. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Devuelve el tiempo de ejecución del proceso en milisegundos.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Devuelve el total de firmas procesadas


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Devuelve el tamaño del documento de origen en bytes


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Devuelve el tamaño del documento de destino. Para la verificación, esta variable siempre contiene cero.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lista de firmas verificadas con éxito [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
Actualmente esta propiedad no es compatible.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista de firmas que fallaron en el proceso de verificación.
Actualmente esta propiedad no es compatible.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Devuelve true si el proceso de verificación fue exitoso, de lo contrario false.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Devuelve true si el proceso de verificación fue exitoso, de lo contrario false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

