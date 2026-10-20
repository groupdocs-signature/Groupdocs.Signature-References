---
title: "ProcessProgressEventArgs"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Proporciona datos para el evento OnProgress de los procesos de verificación y búsqueda de firmas."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Proporciona datos para el evento OnProgress de los procesos de firma, verificación y búsqueda.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getProgress()](#getProgress--) | Representa el progreso en porcentajes. |
|
|  | [setProgress(int value)](#setProgress-int-) | Representa el progreso en porcentajes. |
|
|  | [getTicks()](#getTicks--) | Representa el tiempo transcurrido en milisegundos desde el evento Start del proceso. |
|
|  | [setTicks(long value)](#setTicks-long-) | Representa el tiempo transcurrido en milisegundos desde el evento Start del proceso. |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | Representa la cantidad de firmas procesadas. |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Representa la cantidad de firmas procesadas. |
|
|  | [getCancel()](#getCancel--) | Indica si el proceso debe cancelarse. |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | Indica si el proceso debe cancelarse. |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Representa el progreso en porcentajes. El rango de valores es de 0 a 100.


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Representa el progreso en porcentajes. El rango de valores es de 0 a 100.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Representa el tiempo transcurrido en milisegundos desde el evento Start del proceso.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Representa el tiempo transcurrido en milisegundos desde el evento Start del proceso.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Representa la cantidad de firmas procesadas.


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Representa la cantidad de firmas procesadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Indica si el proceso debe cancelarse.


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Indica si el proceso debe cancelarse.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

