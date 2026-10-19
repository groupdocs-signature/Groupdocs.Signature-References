---
title: "ProcessStartEventHandler"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει έναν delegate μεθόδου που θα διαχειρίζεται τις διαδικασίες στα συμβάντα έναρξης για την επαλήθευση υπογραφής και την αναζήτηση."
type: docs
weight: 16
url: /el/java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

Αντιπροσωπεύει έναν αντιπρόσωπο μεθόδου που θα διαχειρίζεται τις διαδικασίες στα γεγονότα έναρξης για υπογραφή, επαλήθευση και αναζήτηση.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

