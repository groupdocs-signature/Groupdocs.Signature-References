---
title: "ProcessStartEventArgs"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Fornisce dati per l'evento Start del processo di verifica e ricerca della firma."
type: docs
weight: 15
url: /it/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

Fornisce dati per l'evento Start dei processi di firma, verifica e ricerca.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getStarted()](#getStarted--) | Rappresenta il segno temporale dell'inizio del processo. |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | Rappresenta il segno temporale dell'inizio del processo. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Rappresenta la quantità totale di firme da elaborare. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Rappresenta la quantità totale di firme da elaborare. |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Rappresenta il segno temporale dell'inizio del processo.


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Rappresenta il segno temporale dell'inizio del processo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Rappresenta la quantità totale di firme da elaborare.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Rappresenta la quantità totale di firme da elaborare.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

