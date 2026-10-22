---
title: "ProcessProgressEventArgs"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt Daten für das OnProgress‑Ereignis von Signatur‑Verifizierungs‑ und Suchvorgängen bereit."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Stellt Daten für das OnProgress-Ereignis von Signatur-, Verifizierungs- und Suchvorgängen bereit.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getProgress()](#getProgress--) | Stellt den Fortschritt in Prozent dar. |
| [setProgress(int value)](#setProgress-int-) | Stellt den Fortschritt in Prozent dar. |
| [getTicks()](#getTicks--) | Stellt die seit dem Prozess‑Start‑Ereignis vergangene Zeit in Millisekunden dar. |
| [setTicks(long value)](#setTicks-long-) | Stellt die seit dem Prozess‑Start‑Ereignis vergangene Zeit in Millisekunden dar. |
| [getProcessedSignatures()](#getProcessedSignatures--) | Stellt die Menge der verarbeiteten Signaturen dar. |
| [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Stellt die Menge der verarbeiteten Signaturen dar. |
| [getCancel()](#getCancel--) | Gibt an, ob der Prozess abgebrochen werden soll. |
| [setCancel(boolean value)](#setCancel-boolean-) | Gibt an, ob der Prozess abgebrochen werden soll. |
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Stellt den Fortschritt in Prozent dar. Der Wertebereich liegt zwischen 0 und 100.

**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Stellt den Fortschritt in Prozent dar. Der Wertebereich liegt zwischen 0 und 100.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Stellt die seit dem Prozess‑Start‑Ereignis vergangene Zeit in Millisekunden dar.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Stellt die seit dem Prozess‑Start‑Ereignis vergangene Zeit in Millisekunden dar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Stellt die Menge der verarbeiteten Signaturen dar.

**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Stellt die Menge der verarbeiteten Signaturen dar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Gibt an, ob der Prozess abgebrochen werden soll.

**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Gibt an, ob der Prozess abgebrochen werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

