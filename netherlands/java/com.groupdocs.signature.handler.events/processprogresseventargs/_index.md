---
title: "ProcessProgressEventArgs"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Biedt gegevens voor het OnProgress-evenement van ondertekeningsverificatie en zoekprocessen."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Biedt gegevens voor het OnProgress‑evenement van ondertekenings‑, verificatie‑ en zoekprocessen.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getProgress()](#getProgress--) | Geeft voortgang in procenten weer. |
|
|  | [setProgress(int value)](#setProgress-int-) | Geeft voortgang in procenten weer. |
|
|  | [getTicks()](#getTicks--) | Geeft verstreken tijd in milliseconden sinds het proces-Start-evenement weer. |
|
|  | [setTicks(long value)](#setTicks-long-) | Geeft verstreken tijd in milliseconden sinds het proces-Start-evenement weer. |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | Geeft hoeveelheid verwerkte handtekeningen weer. |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Geeft hoeveelheid verwerkte handtekeningen weer. |
|
|  | [getCancel()](#getCancel--) | Geeft aan of het proces moet worden geannuleerd. |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | Geeft aan of het proces moet worden geannuleerd. |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Geeft voortgang in procenten weer. Waardenbereik is van 0 tot 100.


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Geeft voortgang in procenten weer. Waardenbereik is van 0 tot 100.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Geeft verstreken tijd in milliseconden sinds het proces-Start-evenement weer.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Geeft verstreken tijd in milliseconden sinds het proces-Start-evenement weer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Geeft hoeveelheid verwerkte handtekeningen weer.


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Geeft hoeveelheid verwerkte handtekeningen weer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Geeft aan of het proces moet worden geannuleerd.


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Geeft aan of het proces moet worden geannuleerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

