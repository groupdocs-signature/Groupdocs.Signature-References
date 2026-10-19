---
title: "ProcessStartEventArgs"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt Daten für das Startereignis der Signaturüberprüfung und des Suchvorgangs bereit"
type: docs
weight: 15
url: /de/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

Stellt Daten für das Start-Ereignis von Signatur-, Verifizierungs- und Suchvorgängen bereit.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getStarted()](#getStarted--) | Stellt den Zeitstempel des Prozessstarts dar. |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | Stellt den Zeitstempel des Prozessstarts dar. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Stellt die Gesamtanzahl der zu verarbeitenden Signaturen dar. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Stellt die Gesamtanzahl der zu verarbeitenden Signaturen dar. |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Stellt den Zeitstempel des Prozessstarts dar.


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Stellt den Zeitstempel des Prozessstarts dar.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Stellt die Gesamtanzahl der zu verarbeitenden Signaturen dar.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Stellt die Gesamtanzahl der zu verarbeitenden Signaturen dar.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

