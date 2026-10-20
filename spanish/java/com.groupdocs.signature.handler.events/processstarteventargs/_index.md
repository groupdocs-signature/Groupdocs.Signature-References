---
title: "ProcessStartEventArgs"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Proporciona datos para el evento Start de la verificación y búsqueda de firmas"
type: docs
weight: 15
url: /es/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

Proporciona datos para el evento Start del proceso de firma, verificación y búsqueda

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getStarted()](#getStarted--) | Representa la marca de tiempo del inicio del proceso. |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | Representa la marca de tiempo del inicio del proceso. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Representa la cantidad total de firmas que se procesarán. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Representa la cantidad total de firmas que se procesarán. |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Representa la marca de tiempo del inicio del proceso.


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Representa la marca de tiempo del inicio del proceso.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Representa la cantidad total de firmas que se procesarán.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Representa la cantidad total de firmas que se procesarán.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

