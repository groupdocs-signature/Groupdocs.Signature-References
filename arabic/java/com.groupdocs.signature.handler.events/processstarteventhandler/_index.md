---
title: "ProcessStartEventHandler"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل مندوب طريقة سيعالج العمليات عند أحداث البدء للتحقق من التوقيع والبحث."
type: docs
weight: 16
url: /ar/java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

يمثل مفوض طريقة سيعالج العمليات عند أحداث البدء للتوقيع والتحقق والبحث.

## البناؤون

| منشئ | الوصف |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## الطرق

| طريقة | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

