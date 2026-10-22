---
title: "ProcessCompleteEventHandler"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili delegasi metode yang akan menangani proses pada peristiwa selesai untuk verifikasi penandatanganan dan pencarian."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.signature.handler.events/processcompleteeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessCompleteEventHandler extends System.MulticastDelegate
```

Mewakili delegasi metode yang akan menangani proses pada peristiwa selesai untuk penandatanganan, verifikasi, dan pencarian.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ProcessCompleteEventHandler()](#ProcessCompleteEventHandler--) |  |
## Metode

| Metode | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessCompleteEventArgs](../../com.groupdocs.signature.handler.events/processcompleteeventargs) |  |

