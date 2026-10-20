---
title: "DigitalVBA"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "स्प्रेडशीट्स VBA प्रोजेक्ट्स के लिए डिजिटल हस्ताक्षर का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

स्प्रेडशीट्स VBA प्रोजेक्ट्स के लिए डिजिटल हस्ताक्षर का प्रतिनिधित्व करता है।
यह Xlsm या Xltm जैसे विशिष्ट स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट में VBA प्रोजेक्ट पर हस्ताक्षर करने की क्षमता प्रदान करता है।
यदि कई DigitalVBA एक्सटेंशन DigitalSignOptions.Extensions में जोड़े जाते हैं, तो केवल पहला दस्तावेज़ पर हस्ताक्षर में शामिल होता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | प्रमाणपत्र फ़ाइल के साथ DigitalVBA क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | प्रमाणपत्र स्ट्रीम के साथ DigitalVBA क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getComments()](#getComments--) | हस्ताक्षर टिप्पणी प्राप्त करता है या सेट करता है। |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | हस्ताक्षर टिप्पणी प्राप्त करता है या सेट करता है। |
|
|  | [getPassword()](#getPassword--) | डिजिटल प्रमाणपत्र का पासवर्ड प्राप्त करता है या सेट करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | डिजिटल प्रमाणपत्र का पासवर्ड प्राप्त करता है या सेट करता है। |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | केवल VBA प्रोजेक्ट हस्ताक्षर की सेटिंग प्राप्त करता है या सेट करता है। |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | केवल VBA प्रोजेक्ट हस्ताक्षर की सेटिंग प्राप्त करता है या सेट करता है। |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | डिजिटल प्रमाणपत्र फ़ाइल पथ प्राप्त करता है। |
|
|  | [getCertificateStream()](#getCertificateStream--) | डिजिटल प्रमाणपत्र स्ट्रीम प्राप्त करता है। |
|
|  | [release()](#release--) | हस्ताक्षर के बाद संसाधनों को साफ़ करने के लिए ओवरराइड मेथड। |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


प्रमाणपत्र फ़ाइल के साथ DigitalVBA क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | डिजिटल सर्टिफिकेट फ़ाइल पाथ |
|
|  | पासवर्ड | java.lang.String | डिजिटल प्रमाणपत्र पासवर्ड |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


प्रमाणपत्र स्ट्रीम के साथ DigitalVBA क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | डिजिटल सर्टिफिकेट स्ट्रीम |
|
|  | पासवर्ड | java.lang.String | डिजिटल प्रमाणपत्र पासवर्ड |
|

### getComments() {#getComments--}
```
public final String getComments()
```


हस्ताक्षर टिप्पणी प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


हस्ताक्षर टिप्पणी प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


डिजिटल प्रमाणपत्र का पासवर्ड प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


डिजिटल प्रमाणपत्र का पासवर्ड प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


केवल VBA प्रोजेक्ट हस्ताक्षर की सेटिंग प्राप्त करता है या सेट करता है।
यदि true सेट किया गया है, तो स्प्रेडशीट दस्तावेज़ पर हस्ताक्षर नहीं होगा, लेकिन VBA प्रोजेक्ट पर हस्ताक्षर होगा।


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


केवल VBA प्रोजेक्ट हस्ताक्षर की सेटिंग प्राप्त करता है या सेट करता है।
यदि true सेट किया गया है, तो स्प्रेडशीट दस्तावेज़ पर हस्ताक्षर नहीं होगा, लेकिन VBA प्रोजेक्ट पर हस्ताक्षर होगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


डिजिटल प्रमाणपत्र फ़ाइल पथ प्राप्त करता है।
यह प्रॉपर्टी केवल तब उपयोग की जाती है जब CertificateStream निर्दिष्ट नहीं किया गया हो।


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


डिजिटल प्रमाणपत्र स्ट्रीम प्राप्त करता है।
यदि यह प्रॉपर्टी निर्दिष्ट की गई है, तो यह हमेशा CertificateFilePath के बजाय उपयोग की जाती है।


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


हस्ताक्षर के बाद संसाधनों को साफ़ करने के लिए ओवरराइड मेथड।


