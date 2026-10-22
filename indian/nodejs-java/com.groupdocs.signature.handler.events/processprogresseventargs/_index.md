---
title: "ProcessProgressEventArgs"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "साइनिंग सत्यापन और खोज प्रक्रियाओं के ऑनप्रोग्रेस इवेंट के लिए डेटा प्रदान करता है।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

हस्ताक्षर, सत्यापन और खोज प्रक्रियाओं के OnProgress इवेंट के लिए डेटा प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getProgress()](#getProgress--) | प्रगति को प्रतिशत में दर्शाता है। |
| [setProgress(int value)](#setProgress-int-) | प्रगति को प्रतिशत में दर्शाता है। |
| [getTicks()](#getTicks--) | प्रक्रिया स्टार्ट इवेंट से मिलीसेकंड में बीता समय दर्शाता है। |
| [setTicks(long value)](#setTicks-long-) | प्रक्रिया स्टार्ट इवेंट से मिलीसेकंड में बीता समय दर्शाता है। |
| [getProcessedSignatures()](#getProcessedSignatures--) | प्रोसेस किए गए सिग्नेचर की मात्रा दर्शाता है। |
| [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | प्रोसेस किए गए सिग्नेचर की मात्रा दर्शाता है। |
| [getCancel()](#getCancel--) | निर्देशित करता है कि प्रक्रिया को रद्द किया जाना चाहिए या नहीं। |
| [setCancel(boolean value)](#setCancel-boolean-) | निर्देशित करता है कि प्रक्रिया को रद्द किया जाना चाहिए या नहीं। |
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


प्रगति को प्रतिशत में दर्शाता है। मान सीमा 0 से 100 तक है।

**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


प्रगति को प्रतिशत में दर्शाता है। मान सीमा 0 से 100 तक है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


प्रक्रिया स्टार्ट इवेंट से मिलीसेकंड में बीता समय दर्शाता है।

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


प्रक्रिया स्टार्ट इवेंट से मिलीसेकंड में बीता समय दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


प्रोसेस किए गए सिग्नेचर की मात्रा दर्शाता है।

**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


प्रोसेस किए गए सिग्नेचर की मात्रा दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


निर्देशित करता है कि प्रक्रिया को रद्द किया जाना चाहिए या नहीं।

**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


निर्देशित करता है कि प्रक्रिया को रद्द किया जाना चाहिए या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

