---
title: "FileLogger"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "फ़ाइल में लॉग संदेश लिखता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

फ़ाइल में लॉग संदेश लिखता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | फ़ाइल के लिए लॉगर बनाएं। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | कंसोल पर एक त्रुटि संदेश लिखता है। |
|
|  | [trace(String message)](#trace-java.lang.String-) | कंसोल पर ट्रेस संदेश लिखता है। |
|
|  | [warning(String message)](#warning-java.lang.String-) | कंसोल पर चेतावनी संदेश लिखता है; |
चेतावनी लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं की जानकारी प्रदान करते हैं।
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


फ़ाइल के लिए लॉगर बनाएं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileName | java.lang.String | पथ सहित पूर्ण फ़ाइल नाम |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


कंसोल पर एक त्रुटि संदेश लिखता है।
त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं की जानकारी प्रदान करते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | त्रुटि संदेश। |
|
|  | अपवाद | java.lang.Exception | अपवाद। |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


कंसोल पर ट्रेस संदेश लिखता है।
ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | ट्रेस संदेश। |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


कंसोल पर चेतावनी संदेश लिखता है;
चेतावनी लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं की जानकारी प्रदान करते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | चेतावनी संदेश। |
|

