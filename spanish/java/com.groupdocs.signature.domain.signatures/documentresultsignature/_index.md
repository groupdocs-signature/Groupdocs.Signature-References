---
title: "DocumentResultSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Resultado del proceso de firma de documento de archivo para un documento con firmas recién creadas."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Resultado del proceso de firma de documento de archivo para un documento con firmas recién creadas.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFileName()](#getFileName--) | Nombre del archivo del documento |
|
|  | [getProcessingTime()](#getProcessingTime--) | Devuelve el tiempo de ejecución del proceso en milisegundos |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Devuelve el total de firmas procesadas |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Devuelve el tamaño del documento de origen |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Devuelve el tamaño del documento de destino |
|
|  | [getSucceeded()](#getSucceeded--) | Lista de firmas procesadas con éxito [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista de las firmas que fallaron durante el proceso [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | si el documento se procesó con error, esta propiedad contendrá el mensaje de error |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Nombre del archivo del documento


**Returns:**
java.lang.String
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


Lista de firmas procesadas con éxito [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista de las firmas que fallaron durante el proceso [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


si el documento se procesó con error, esta propiedad contendrá el mensaje de error


**Returns:**
java.lang.String
