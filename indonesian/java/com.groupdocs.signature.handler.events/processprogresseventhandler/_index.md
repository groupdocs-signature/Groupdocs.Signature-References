---
title: "ProcessProgressEventHandler"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili delegasi metode yang akan menangani proses pada peristiwa kemajuan untuk verifikasi penandatanganan dan pencarian."
type: docs
weight: 14
url: /id/java/com.groupdocs.signature.handler.events/processprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessProgressEventHandler extends System.MulticastDelegate
```

Mewakili delegasi metode yang akan menangani proses pada peristiwa kemajuan untuk penandatanganan, verifikasi, dan pencarian.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ProcessProgressEventHandler()](#ProcessProgressEventHandler--) |  |
## Metode

| Metode | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessProgressEventArgs](../../com.groupdocs.signature.handler.events/processprogresseventargs) |  |

