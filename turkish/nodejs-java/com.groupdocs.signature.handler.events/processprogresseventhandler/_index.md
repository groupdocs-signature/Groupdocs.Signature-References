---
title: "ProcessProgressEventHandler"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "İmza doğrulama ve arama için ilerleme olaylarında süreçleri yönetecek bir yöntem temsilcisini temsil eder."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.signature.handler.events/processprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessProgressEventHandler extends System.MulticastDelegate
```

İmzalama, doğrulama ve arama için ilerleme olaylarında süreçleri yönetecek bir yöntem temsilcisini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ProcessProgressEventHandler()](#ProcessProgressEventHandler--) |  |
## Yöntemler

| Yöntem | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessProgressEventArgs](../../com.groupdocs.signature.handler.events/processprogresseventargs) |  |

