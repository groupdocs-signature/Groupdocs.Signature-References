---
title: "ProcessCompleteEventHandler"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt een methodedelegate voor die processen afhandelt bij voltooiingsevenementen voor ondertekeningsverificatie en zoeken."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.handler.events/processcompleteeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessCompleteEventHandler extends System.MulticastDelegate
```

Stelt een methodedelegate voor die processen afhandelt bij voltooiings‑evenementen voor ondertekening, verificatie en zoeken.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ProcessCompleteEventHandler()](#ProcessCompleteEventHandler--) |  |
## Methoden

| Methode | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessCompleteEventArgs](../../com.groupdocs.signature.handler.events/processcompleteeventargs) |  |

