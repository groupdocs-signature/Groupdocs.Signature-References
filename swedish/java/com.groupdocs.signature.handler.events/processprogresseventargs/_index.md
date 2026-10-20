---
title: "ProcessProgressEventArgs"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Tillhandahåller data för OnProgress‑händelse för signaturverifiering och sökprocesser."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Tillhandahåller data för OnProgress‑händelsen för signering, verifiering och sökprocesser.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getProgress()](#getProgress--) | Representerar framsteg i procent. |
|
|  | [setProgress(int value)](#setProgress-int-) | Representerar framsteg i procent. |
|
|  | [getTicks()](#getTicks--) | Representerar tid som spenderats i millisekunder sedan processens Start‑händelse. |
|
|  | [setTicks(long value)](#setTicks-long-) | Representerar tid som spenderats i millisekunder sedan processens Start‑händelse. |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | Representerar mängden bearbetade signaturer. |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Representerar mängden bearbetade signaturer. |
|
|  | [getCancel()](#getCancel--) | Indikerar om processen ska avbrytas. |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | Indikerar om processen ska avbrytas. |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Representerar framsteg i procent. Värdeintervallet är från 0 till 100.


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Representerar framsteg i procent. Värdeintervallet är från 0 till 100.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Representerar tid som spenderats i millisekunder sedan processens Start‑händelse.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Representerar tid som spenderats i millisekunder sedan processens Start‑händelse.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Representerar mängden bearbetade signaturer.


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Representerar mängden bearbetade signaturer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Indikerar om processen ska avbrytas.


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Indikerar om processen ska avbrytas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

