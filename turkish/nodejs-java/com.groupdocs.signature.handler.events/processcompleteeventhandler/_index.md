---
title: "ProcessCompleteEventHandler"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "İmza doğrulama ve arama için tamamlama olaylarında işlemleri yönetecek bir yöntem temsilcisini temsil eder."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature.handler.events/processcompleteeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessCompleteEventHandler extends System.MulticastDelegate
```

İmzalama, doğrulama ve arama için tam olaylarda süreçleri yönetecek bir yöntem temsilcisini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ProcessCompleteEventHandler()](#ProcessCompleteEventHandler--) |  |
## Yöntemler

| Yöntem | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessCompleteEventArgs](../../com.groupdocs.signature.handler.events/processcompleteeventargs) |  |

