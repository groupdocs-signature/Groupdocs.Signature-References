---
title: "ProcessCompleteEventArgs"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Tillhandahåller data för slutförandehändelsen av signaturverifierings- och sökprocesser."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Tillhandahåller data om fullständiga händelser för signering, verifiering och sökprocesser.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | Representerar tidsstämpeln för processens slutförande. |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | Representerar tidsstämpeln för processens slutförande. |
|
|  | [getTicks()](#getTicks--) | Representerar tid i millisekunder som förflutit sedan processens Start‑händelse. |
|
|  | [setTicks(long value)](#setTicks-long-) | Representerar tid i millisekunder som förflutit sedan processens Start‑händelse. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Representerar total mängd av bearbetade signaturer. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Representerar total mängd av bearbetade signaturer. |
|
|  | [getCanceled()](#getCanceled--) | Anger om processen avbröts. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Representerar tidsstämpeln för processens slutförande.


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Representerar tidsstämpeln för processens slutförande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Representerar tid i millisekunder som förflutit sedan processens Start‑händelse.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Representerar tid i millisekunder som förflutit sedan processens Start‑händelse.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Representerar total mängd av bearbetade signaturer.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Representerar total mängd av bearbetade signaturer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Anger om processen avbröts.


**Returns:**
boolean
