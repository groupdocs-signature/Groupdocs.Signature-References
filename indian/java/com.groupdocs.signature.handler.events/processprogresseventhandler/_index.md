---
title: "ProcessProgressEventHandler"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "एक मेथड डेलीगेट को दर्शाता है जो साइनिंग सत्यापन और खोज के प्रगति इवेंट्स पर प्रक्रियाओं को संभालेगा।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.signature.handler.events/processprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessProgressEventHandler extends System.MulticastDelegate
```

एक मेथड डेलीगेट का प्रतिनिधित्व करता है जो हस्ताक्षर, सत्यापन और खोज के प्रगति घटनाओं पर प्रक्रियाओं को संभालेगा।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ProcessProgressEventHandler()](#ProcessProgressEventHandler--) |  |
## मेथड्स

| मेथड | विवरण |
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessProgressEventArgs](../../com.groupdocs.signature.handler.events/processprogresseventargs) |  |

