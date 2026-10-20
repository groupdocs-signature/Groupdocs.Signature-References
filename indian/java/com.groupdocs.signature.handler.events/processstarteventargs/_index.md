---
title: "ProcessStartEventArgs"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "हस्ताक्षर सत्यापन और खोज प्रक्रिया के प्रारंभ इवेंट के लिए डेटा प्रदान करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

हस्ताक्षर, सत्यापन और खोज प्रक्रिया के Start इवेंट के लिए डेटा प्रदान करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getStarted()](#getStarted--) | प्रक्रिया प्रारंभ का समय चिह्न दर्शाता है। |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | प्रक्रिया प्रारंभ का समय चिह्न दर्शाता है। |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | प्रसंस्करण के लिए कुल हस्ताक्षरों की मात्रा दर्शाता है। |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | प्रसंस्करण के लिए कुल हस्ताक्षरों की मात्रा दर्शाता है। |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


प्रक्रिया प्रारंभ का समय चिह्न दर्शाता है।


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


प्रक्रिया प्रारंभ का समय चिह्न दर्शाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


प्रसंस्करण के लिए कुल हस्ताक्षरों की मात्रा दर्शाता है।


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


प्रसंस्करण के लिए कुल हस्ताक्षरों की मात्रा दर्शाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

