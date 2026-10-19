---
title: "ProcessCompleteEventArgs"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt Daten zum Abschlussereignis der Signaturüberprüfung und Suchvorgänge bereit."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Stellt Daten zum Abschlussereignis von Signatur-, Verifizierungs- und Suchvorgängen bereit.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | Stellt den Zeitstempel des Prozessabschlusses dar. |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | Stellt den Zeitstempel des Prozessabschlusses dar. |
|
|  | [getTicks()](#getTicks--) | Stellt die seit dem Prozess-Startereignis vergangene Zeit in Millisekunden dar. |
|
|  | [setTicks(long value)](#setTicks-long-) | Stellt die seit dem Prozess-Startereignis vergangene Zeit in Millisekunden dar. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Stellt die Gesamtmenge der verarbeiteten Signaturen dar. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Stellt die Gesamtmenge der verarbeiteten Signaturen dar. |
|
|  | [getCanceled()](#getCanceled--) | Gibt an, ob der Vorgang abgebrochen wurde. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Stellt den Zeitstempel des Prozessabschlusses dar.


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Stellt den Zeitstempel des Prozessabschlusses dar.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Stellt die seit dem Prozess-Startereignis vergangene Zeit in Millisekunden dar.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Stellt die seit dem Prozess-Startereignis vergangene Zeit in Millisekunden dar.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Stellt die Gesamtmenge der verarbeiteten Signaturen dar.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Stellt die Gesamtmenge der verarbeiteten Signaturen dar.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Gibt an, ob der Vorgang abgebrochen wurde.


**Returns:**
boolean
