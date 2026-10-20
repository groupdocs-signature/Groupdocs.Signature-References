---
title: "ProcessStartEventHandler"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "एक मेथड डेलीगेट को दर्शाता है जो हस्ताक्षर सत्यापन और खोज के प्रारंभ इवेंट पर प्रक्रियाओं को संभालेगा।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

एक मेथड डेलीगेट का प्रतिनिधित्व करता है जो हस्ताक्षर, सत्यापन और खोज के प्रारंभिक घटनाओं पर प्रक्रियाओं को संभालेगा।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## मेथड्स

| मेथड | विवरण |
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

