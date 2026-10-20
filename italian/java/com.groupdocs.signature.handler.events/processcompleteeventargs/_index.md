---
title: "ProcessCompleteEventArgs"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Fornisce dati sull'evento di completamento dei processi di verifica della firma e di ricerca."
type: docs
weight: 10
url: /it/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Fornisce dati sull'evento di completamento dei processi di firma, verifica e ricerca.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | Rappresenta il segno temporale del completamento del processo. |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | Rappresenta il segno temporale del completamento del processo. |
|
|  | [getTicks()](#getTicks--) | Rappresenta il tempo in millisecondi trascorso dall'evento di avvio del processo. |
|
|  | [setTicks(long value)](#setTicks-long-) | Rappresenta il tempo in millisecondi trascorso dall'evento di avvio del processo. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Rappresenta la quantità totale di firme elaborate. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Rappresenta la quantità totale di firme elaborate. |
|
|  | [getCanceled()](#getCanceled--) | Indica se il processo è stato annullato. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Rappresenta il segno temporale del completamento del processo.


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Rappresenta il segno temporale del completamento del processo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Rappresenta il tempo in millisecondi trascorso dall'evento di avvio del processo.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Rappresenta il tempo in millisecondi trascorso dall'evento di avvio del processo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Rappresenta la quantità totale di firme elaborate.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Rappresenta la quantità totale di firme elaborate.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Indica se il processo è stato annullato.


**Returns:**
boolean
