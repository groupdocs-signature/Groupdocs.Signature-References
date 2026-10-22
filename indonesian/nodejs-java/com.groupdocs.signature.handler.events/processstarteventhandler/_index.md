---
title: "ProcessStartEventHandler"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili delegasi metode yang akan menangani proses pada peristiwa start untuk verifikasi penandatanganan dan pencarian."
type: docs
weight: 16
url: /id/nodejs-java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

Mewakili delegasi metode yang akan menangani proses pada peristiwa mulai untuk penandatanganan, verifikasi, dan pencarian.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## Metode

| Metode | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

