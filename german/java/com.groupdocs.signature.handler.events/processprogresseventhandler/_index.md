---
title: "ProcessProgressEventHandler"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt einen Methodendelegaten dar, der Prozesse bei Fortschrittsereignissen für die Signaturüberprüfung und Suche verarbeitet."
type: docs
weight: 14
url: /de/java/com.groupdocs.signature.handler.events/processprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessProgressEventHandler extends System.MulticastDelegate
```

Stellt einen Methodendelegaten dar, der Prozesse bei Fortschrittsereignissen für Signatur, Verifizierung und Suche behandelt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ProcessProgressEventHandler()](#ProcessProgressEventHandler--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(Signature signature, ProcessProgressEventArgs args)](#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessProgressEventArgs-) |  |
### ProcessProgressEventHandler() {#ProcessProgressEventHandler--}
```
public ProcessProgressEventHandler()
```


### invoke(Signature signature, ProcessProgressEventArgs args) {#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessProgressEventArgs-}
```
public abstract void invoke(Signature signature, ProcessProgressEventArgs args)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessProgressEventArgs](../../com.groupdocs.signature.handler.events/processprogresseventargs) |  |

