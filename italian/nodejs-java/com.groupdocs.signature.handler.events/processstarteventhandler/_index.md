---
title: "ProcessStartEventHandler"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta un delegato di metodo che gestirà i processi sugli eventi di avvio per la verifica e la ricerca della firma."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

Rappresenta un delegato di metodo che gestirà i processi sugli eventi di avvio per la firma, la verifica e la ricerca.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## Metodi

| Metodo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

