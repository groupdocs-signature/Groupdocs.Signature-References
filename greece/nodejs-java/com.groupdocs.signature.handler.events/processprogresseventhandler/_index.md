---
title: "ProcessProgressEventHandler"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αναπαριστά έναν delegate μεθόδου που θα διαχειρίζεται τις διαδικασίες στα συμβάντα προόδου για την επαλήθευση υπογραφής και την αναζήτηση."
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.signature.handler.events/processprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessProgressEventHandler extends System.MulticastDelegate
```

Αντιπροσωπεύει έναν delegate μεθόδου που θα διαχειρίζεται τις διαδικασίες σε γεγονότα προόδου για υπογραφή, επαλήθευση και αναζήτηση.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ProcessProgressEventHandler()](#ProcessProgressEventHandler--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessProgressEventArgs](../../com.groupdocs.signature.handler.events/processprogresseventargs) |  |

