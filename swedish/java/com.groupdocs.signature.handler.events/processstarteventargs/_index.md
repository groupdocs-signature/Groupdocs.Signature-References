---
title: "ProcessStartEventArgs"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Tillhandahåller data för Start‑händelse för signaturverifiering och sökprocess."
type: docs
weight: 15
url: /sv/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

Tillhandahåller data för Start‑händelsen för signering, verifiering och sökprocess.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getStarted()](#getStarted--) | Representerar tidsmärke för processens start. |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | Representerar tidsmärke för processens start. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Representerar total mängd signaturer som ska bearbetas. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Representerar total mängd signaturer som ska bearbetas. |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Representerar tidsmärke för processens start.


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Representerar tidsmärke för processens start.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Representerar total mängd signaturer som ska bearbetas.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Representerar total mängd signaturer som ska bearbetas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

