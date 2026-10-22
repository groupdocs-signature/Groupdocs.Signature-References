---
title: "ProcessCompleteEventHandler"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αναπαριστά έναν delegate μεθόδου που θα χειρίζεται τις διαδικασίες στα γεγονότα ολοκλήρωσης για την επαλήθευση υπογραφής και την αναζήτηση."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.signature.handler.events/processcompleteeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessCompleteEventHandler extends System.MulticastDelegate
```

Αντιπροσωπεύει έναν delegate μεθόδου που θα διαχειρίζεται τις διαδικασίες σε πλήρη γεγονότα για υπογραφή, επαλήθευση και αναζήτηση.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ProcessCompleteEventHandler()](#ProcessCompleteEventHandler--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessCompleteEventArgs](../../com.groupdocs.signature.handler.events/processcompleteeventargs) |  |

