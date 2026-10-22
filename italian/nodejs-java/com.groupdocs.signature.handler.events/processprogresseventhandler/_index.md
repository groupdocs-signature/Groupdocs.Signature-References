---
title: "ProcessProgressEventHandler"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta un delegato di metodo che gestirà i processi sugli eventi di avanzamento per la verifica e la ricerca della firma."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.signature.handler.events/processprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessProgressEventHandler extends System.MulticastDelegate
```

Rappresenta un delegato di metodo che gestirà i processi sugli eventi di avanzamento per la firma, la verifica e la ricerca.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ProcessProgressEventHandler()](#ProcessProgressEventHandler--) |  |
## Metodi

| Metodo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessProgressEventArgs](../../com.groupdocs.signature.handler.events/processprogresseventargs) |  |

