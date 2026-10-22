---
title: "ProcessCompleteEventArgs"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "हस्ताक्षर सत्यापन और खोज प्रक्रियाओं की पूर्ण घटना पर डेटा प्रदान करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

हस्ताक्षर, सत्यापन और खोज प्रक्रियाओं के पूर्ण इवेंट पर डेटा प्रदान करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCompleted()](#getCompleted--) | प्रक्रिया पूर्णता का समय चिह्न दर्शाता है। |
| [setCompleted(Date value)](#setCompleted-java.util.Date-) | प्रक्रिया पूर्णता का समय चिह्न दर्शाता है। |
| [getTicks()](#getTicks--) | प्रक्रिया प्रारम्भ घटना से अब तक बिताए गए मिलीसेकंड में समय को दर्शाता है। |
| [setTicks(long value)](#setTicks-long-) | प्रक्रिया प्रारम्भ घटना से अब तक बिताए गए मिलीसेकंड में समय को दर्शाता है। |
| [getTotalSignatures()](#getTotalSignatures--) | प्रसंस्कृत हस्ताक्षरों की कुल मात्रा दर्शाता है। |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | प्रसंस्कृत हस्ताक्षरों की कुल मात्रा दर्शाता है। |
| [getCanceled()](#getCanceled--) | संकेत करता है कि प्रक्रिया रद्द की गई थी या नहीं। |
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


प्रक्रिया पूर्णता का समय चिह्न दर्शाता है।

**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


प्रक्रिया पूर्णता का समय चिह्न दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


प्रक्रिया प्रारम्भ घटना से अब तक बिताए गए मिलीसेकंड में समय को दर्शाता है।

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


प्रक्रिया प्रारम्भ घटना से अब तक बिताए गए मिलीसेकंड में समय को दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


प्रसंस्कृत हस्ताक्षरों की कुल मात्रा दर्शाता है।

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


प्रसंस्कृत हस्ताक्षरों की कुल मात्रा दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


संकेत करता है कि प्रक्रिया रद्द की गई थी या नहीं।

**Returns:**
boolean
