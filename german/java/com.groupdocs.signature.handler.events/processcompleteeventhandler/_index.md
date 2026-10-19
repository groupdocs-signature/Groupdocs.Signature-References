---
title: "ProcessCompleteEventHandler"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt einen Methodendelegaten dar, der Prozesse bei abgeschlossenen Ereignissen für die Signaturüberprüfung und Suche behandelt."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.handler.events/processcompleteeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessCompleteEventHandler extends System.MulticastDelegate
```

Stellt einen Methodendelegaten dar, der Prozesse bei Abschlussereignissen für Signatur, Verifizierung und Suche behandelt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ProcessCompleteEventHandler()](#ProcessCompleteEventHandler--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(Signature signature, ProcessCompleteEventArgs args)](#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessCompleteEventArgs-) |  |
### ProcessCompleteEventHandler() {#ProcessCompleteEventHandler--}
```
public ProcessCompleteEventHandler()
```


### invoke(Signature signature, ProcessCompleteEventArgs args) {#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessCompleteEventArgs-}
```
public abstract void invoke(Signature signature, ProcessCompleteEventArgs args)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessCompleteEventArgs](../../com.groupdocs.signature.handler.events/processcompleteeventargs) |  |

