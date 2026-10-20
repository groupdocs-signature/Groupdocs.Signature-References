---
title: "ProcessStartEventHandler"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt een methodedelegate die processen afhandelt bij start-evenementen voor ondertekeningsverificatie en zoeken."
type: docs
weight: 16
url: /nl/java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

Stelt een methodedelegate voor die processen afhandelt bij start‑evenementen voor ondertekening, verificatie en zoeken.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## Methoden

| Methode | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

