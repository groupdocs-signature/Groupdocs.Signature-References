---
title: "DeleteResult"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Resultado de la eliminación de firmas del documento."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Resultado de la eliminación de firma(s) del documento.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Devuelve el tiempo de ejecución del proceso en milisegundos. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Devuelve el total de firmas procesadas. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Devuelve el tamaño del documento fuente. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Devuelve el tamaño actualizado del documento. |
|
|  | [getSucceeded()](#getSucceeded--) | Lista de firmas eliminadas con éxito [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista de firmas que no fueron eliminadas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
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


Devuelve el total de firmas procesadas.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Devuelve el tamaño del documento fuente.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Devuelve el tamaño actualizado del documento.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lista de firmas eliminadas con éxito [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista de firmas que no fueron eliminadas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
