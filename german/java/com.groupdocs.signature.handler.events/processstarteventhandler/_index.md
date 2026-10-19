---
title: "ProcessStartEventHandler"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt einen Methodendelegaten dar, der Prozesse bei Startereignissen für die Signaturüberprüfung und Suche verarbeitet."
type: docs
weight: 16
url: /de/java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

Stellt einen Methodendelegaten dar, der Prozesse bei Startereignissen für Signatur, Verifizierung und Suche behandelt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(Signature signature, ProcessStartEventArgs args)](#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessStartEventArgs-) |  |
### ProcessStartEventHandler() {#ProcessStartEventHandler--}
```
public ProcessStartEventHandler()
```


### invoke(Signature signature, ProcessStartEventArgs args) {#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessStartEventArgs-}
```
public abstract void invoke(Signature signature, ProcessStartEventArgs args)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

