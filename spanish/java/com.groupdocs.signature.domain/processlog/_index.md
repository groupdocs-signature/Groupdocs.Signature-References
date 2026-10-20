---
title: "ProcessLog"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa detalles del proceso de documento."
type: docs
weight: 15
url: /es/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Representa detalles del proceso de documento.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getDate()](#getDate--) | Obtener la fecha y hora del proceso. |
|
|  | [getType()](#getType--) | Obtener el tipo de proceso. |
|
|  | [getMessage()](#getMessage--) | Obtener la descripción del proceso. |
|
|  | [getSucceeded()](#getSucceeded--) | Cantidad de firmas procesadas con éxito. |
|
|  | [getFailed()](#getFailed--) | Cantidad de firmas que fallaron durante el procesamiento. |
|
|  | [getSignatures()](#getSignatures--) | La lista de firmas procesadas con éxito. |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


Obtener la fecha y hora del proceso.


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Obtener el tipo de proceso.


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Obtener la descripción del proceso.


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Cantidad de firmas procesadas con éxito.


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Cantidad de firmas que fallaron durante el procesamiento.


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


La lista de firmas procesadas con éxito.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
