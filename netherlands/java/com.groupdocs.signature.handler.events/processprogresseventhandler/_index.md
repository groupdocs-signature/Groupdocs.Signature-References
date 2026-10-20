---
title: "ProcessProgressEventHandler"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt een methodedelegate die processen afhandelt bij voortgang-evenementen voor ondertekeningsverificatie en zoeken."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.handler.events/processprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessProgressEventHandler extends System.MulticastDelegate
```

Stelt een methodedelegate voor die processen afhandelt bij voortgangs‑evenementen voor ondertekening, verificatie en zoeken.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ProcessProgressEventHandler()](#ProcessProgressEventHandler--) |  |
## Methoden

| Methode | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessProgressEventArgs](../../com.groupdocs.signature.handler.events/processprogresseventargs) |  |

