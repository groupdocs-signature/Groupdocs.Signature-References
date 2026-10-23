---
title: "ProcessStartEventHandler"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "İmza doğrulama ve arama için start events sırasında süreçleri yönetecek bir yöntem temsilcisini temsil eder."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

İmzalama, doğrulama ve arama için başlangıç olaylarında süreçleri yönetecek bir yöntem temsilcisini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## Yöntemler

| Yöntem | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

