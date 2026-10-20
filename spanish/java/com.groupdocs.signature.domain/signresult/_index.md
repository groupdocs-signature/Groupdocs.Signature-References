---
title: "SignResult"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Resultado del proceso de firma del documento con firmas recién creadas."
type: docs
weight: 17
url: /es/java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Resultado del proceso de firma del documento con firmas recién creadas.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Devuelve el tiempo de ejecución del proceso en milisegundos |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Devuelve el total de firmas procesadas |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Devuelve el tamaño del documento de origen |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Devuelve el tamaño del documento de destino |
|
|  | [getSucceeded()](#getSucceeded--) | Lista de firmas recién creadas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista de firmas que no se pudieron crear. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Devuelve el tiempo de ejecución del proceso en milisegundos


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


Devuelve el tamaño del documento de origen


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Devuelve el tamaño del documento de destino


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lista de firmas recién creadas [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista de firmas que no se pudieron crear.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
