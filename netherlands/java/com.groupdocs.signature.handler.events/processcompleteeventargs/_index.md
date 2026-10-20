---
title: "ProcessCompleteEventArgs"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Biedt gegevens over het voltooiingsevenement van ondertekeningsverificatie- en zoekprocessen."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Biedt gegevens over het voltooiings‑evenement van ondertekenings‑, verificatie‑ en zoekprocessen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | Stelt het tijdstempel van procesvoltooiing voor. |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | Stelt het tijdstempel van procesvoltooiing voor. |
|
|  | [getTicks()](#getTicks--) | Stelt de tijd in milliseconden voor die is verstreken sinds het proces Start‑evenement. |
|
|  | [setTicks(long value)](#setTicks-long-) | Stelt de tijd in milliseconden voor die is verstreken sinds het proces Start‑evenement. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Stelt de totale hoeveelheid verwerkte handtekeningen voor. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Stelt de totale hoeveelheid verwerkte handtekeningen voor. |
|
|  | [getCanceled()](#getCanceled--) | Geeft aan of het proces is geannuleerd. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Stelt het tijdstempel van procesvoltooiing voor.


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Stelt het tijdstempel van procesvoltooiing voor.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Stelt de tijd in milliseconden voor die is verstreken sinds het proces Start‑evenement.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Stelt de tijd in milliseconden voor die is verstreken sinds het proces Start‑evenement.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Stelt de totale hoeveelheid verwerkte handtekeningen voor.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Stelt de totale hoeveelheid verwerkte handtekeningen voor.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Geeft aan of het proces is geannuleerd.


**Returns:**
boolean
