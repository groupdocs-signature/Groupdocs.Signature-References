---
title: "ProcessCompleteEventHandler"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "एक मेथड डेलीगेट को दर्शाता है जो साइनिंग सत्यापन और खोज के पूर्ण इवेंट्स पर प्रक्रियाओं को संभालेगा।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.handler.events/processcompleteeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessCompleteEventHandler extends System.MulticastDelegate
```

एक मेथड डेलीगेट का प्रतिनिधित्व करता है जो हस्ताक्षर, सत्यापन और खोज के पूर्ण घटनाओं पर प्रक्रियाओं को संभालेगा।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ProcessCompleteEventHandler()](#ProcessCompleteEventHandler--) |  |
## मेथड्स

| मेथड | विवरण |
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessCompleteEventArgs](../../com.groupdocs.signature.handler.events/processcompleteeventargs) |  |

