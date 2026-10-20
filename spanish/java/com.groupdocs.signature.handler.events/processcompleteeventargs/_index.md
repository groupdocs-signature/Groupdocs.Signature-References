---
title: "ProcessCompleteEventArgs"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Proporciona datos del evento Complete de los procesos de verificación y búsqueda de firmas."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Proporciona datos sobre el evento de finalización de los procesos de firma, verificación y búsqueda.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | Representa la marca de tiempo de la finalización del proceso. |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | Representa la marca de tiempo de la finalización del proceso. |
|
|  | [getTicks()](#getTicks--) | Representa el tiempo en milisegundos transcurrido desde el evento Start del proceso. |
|
|  | [setTicks(long value)](#setTicks-long-) | Representa el tiempo en milisegundos transcurrido desde el evento Start del proceso. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Representa la cantidad total de firmas procesadas. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Representa la cantidad total de firmas procesadas. |
|
|  | [getCanceled()](#getCanceled--) | Indica si el proceso fue cancelado. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Representa la marca de tiempo de la finalización del proceso.


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Representa la marca de tiempo de la finalización del proceso.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Representa el tiempo en milisegundos transcurrido desde el evento Start del proceso.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Representa el tiempo en milisegundos transcurrido desde el evento Start del proceso.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Representa la cantidad total de firmas procesadas.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Representa la cantidad total de firmas procesadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Indica si el proceso fue cancelado.


**Returns:**
boolean
