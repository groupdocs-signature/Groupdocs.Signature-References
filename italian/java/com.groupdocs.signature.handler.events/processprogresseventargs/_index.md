---
title: "ProcessProgressEventArgs"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Fornisce dati per l'evento OnProgress dei processi di verifica e ricerca della firma."
type: docs
weight: 13
url: /it/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Fornisce dati per l'evento OnProgress dei processi di firma, verifica e ricerca.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getProgress()](#getProgress--) | Rappresenta il progresso in percentuale. |
|
|  | [setProgress(int value)](#setProgress-int-) | Rappresenta il progresso in percentuale. |
|
|  | [getTicks()](#getTicks--) | Rappresenta il tempo trascorso in millisecondi dall'evento Start del processo. |
|
|  | [setTicks(long value)](#setTicks-long-) | Rappresenta il tempo trascorso in millisecondi dall'evento Start del processo. |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | Rappresenta la quantità di firme elaborate. |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Rappresenta la quantità di firme elaborate. |
|
|  | [getCancel()](#getCancel--) | Indica se il processo dovrebbe essere annullato. |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | Indica se il processo dovrebbe essere annullato. |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Rappresenta il progresso in percentuale. L'intervallo di valori è da 0 a 100.


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Rappresenta il progresso in percentuale. L'intervallo di valori è da 0 a 100.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Rappresenta il tempo trascorso in millisecondi dall'evento Start del processo.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Rappresenta il tempo trascorso in millisecondi dall'evento Start del processo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Rappresenta la quantità di firme elaborate.


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Rappresenta la quantità di firme elaborate.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Indica se il processo dovrebbe essere annullato.


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Indica se il processo dovrebbe essere annullato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

