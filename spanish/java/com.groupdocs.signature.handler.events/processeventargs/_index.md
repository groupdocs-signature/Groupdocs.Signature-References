---
title: "ProcessEventArgs"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Proporciona datos para diferentes eventos de los procesos de verificación y búsqueda de firmas."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.handler.events/processeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ProcessEventArgs extends System.EventArgs
```

Proporciona datos para diferentes eventos de los procesos de firma, verificación y búsqueda.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ProcessEventArgs()](#ProcessEventArgs--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFilePath()](#getFilePath--) | Representa el nombre de archivo del documento procesado. |
|
|  | [setFilePath(String value)](#setFilePath-java.lang.String-) | Representa el nombre de archivo del documento procesado. |
|
|  | [getStatus()](#getStatus--) | Indica el estado actual del proceso. |
|
|  | [setStatus(int value)](#setStatus-int-) | Indica el estado actual del proceso. |
|
### ProcessEventArgs() {#ProcessEventArgs--}
```
public ProcessEventArgs()
```


### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Representa el nombre de archivo del documento procesado.


**Returns:**
java.lang.String
### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public final void setFilePath(String value)
```


Representa el nombre de archivo del documento procesado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


Indica el estado actual del proceso.


**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Indica el estado actual del proceso.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

