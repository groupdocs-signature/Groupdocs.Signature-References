---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "डिजिटल हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

डिजिटल हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | डिफ़ॉल्ट मानों के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | प्रमाणपत्र फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | प्रमाणपत्र स्ट्रीम के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | प्रमाणपत्र फ़ाइल और इमेज फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | प्रमाणपत्र फ़ाइल और इमेज स्ट्रीम के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | प्रमाणपत्र स्ट्रीम और इमेज फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | प्रमाणपत्र स्ट्रीम और इमेज स्ट्रीम के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getReason()](#getReason--) | हस्ताक्षर का कारण प्राप्त करता है या सेट करता है। |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | हस्ताक्षर का कारण प्राप्त करता है या सेट करता है। |
|
|  | [getContact()](#getContact--) | हस्ताक्षर संपर्क को प्राप्त करता है या सेट करता है। |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | हस्ताक्षर संपर्क को प्राप्त करता है या सेट करता है। |
|
|  | [getLocation()](#getLocation--) | हस्ताक्षर स्थान को प्राप्त करता है या सेट करता है। |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | हस्ताक्षर स्थान को प्राप्त करता है या सेट करता है। |
|
|  | [getPassword()](#getPassword--) | डिजिटल प्रमाणपत्र का पासवर्ड प्राप्त करता है या सेट करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | डिजिटल प्रमाणपत्र का पासवर्ड प्राप्त करता है या सेट करता है। |
|
|  | [getSignature()](#getSignature--) | डॉक्यूमेंट डिजिटल सिग्नेचर की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | डॉक्यूमेंट डिजिटल सिग्नेचर की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | डिजिटल सर्टिफिकेट फ़ाइल पाथ को प्राप्त करता है या सेट करता है। |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | डिजिटल सर्टिफिकेट फ़ाइल GUID को प्राप्त करता है या सेट करता है। |
|
|  | [getCertificateStream()](#getCertificateStream--) | डिजिटल सर्टिफिकेट स्ट्रीम को प्राप्त करता है या सेट करता है। |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | डिजिटल सर्टिफिकेट स्ट्रीम को प्राप्त करता है या सेट करता है। |
|
|  | [getVisible()](#getVisible--) | सिग्नेचर की विज़िबिलिटी को प्राप्त करता है या सेट करता है। |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | सिग्नेचर की विज़िबिलिटी को प्राप्त करता है या सेट करता है। |
|
|  | [getUseLtv()](#getUseLtv--) | LTV (Long Term Validation) वैलिडेशन फ़्लैग को प्राप्त/सेट करता है। |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | LTV (Long Term Validation) वैलिडेशन फ़्लैग को प्राप्त/सेट करता है। |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | कस्टम हैश-साइनिंग इम्प्लीमेंटेशन को प्राप्त करता है या सेट करता है, जिससे कॉलर्स अपने स्वयं के |
डिजिटल साइनिंग लॉजिक (HSM, रिमोट साइनर, सॉफ्टवेयर कीस्टोर, आदि)।
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | कस्टम हैश-साइनिंग इम्प्लीमेंटेशन सेट करता है, जिससे कॉलर्स अपने स्वयं के |
डिजिटल साइनिंग लॉजिक।
|
|  | [getXAdESType()](#getXAdESType--) | XAdES प्रकार |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES प्रकार |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


डिफ़ॉल्ट मानों के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


प्रमाणपत्र फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | डिजिटल सर्टिफिकेट फ़ाइल पाथ |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


प्रमाणपत्र स्ट्रीम के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | डिजिटल सर्टिफिकेट स्ट्रीम |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


प्रमाणपत्र फ़ाइल और इमेज फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | डिजिटल सर्टिफिकेट फ़ाइल पाथ |
|
|  | imageFilePath | java.lang.String | सिग्नेचर अपीयरेंस इमेज फ़ाइल पाथ |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


प्रमाणपत्र फ़ाइल और इमेज स्ट्रीम के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | डिजिटल सर्टिफिकेट फ़ाइल पाथ |
|
|  | appearenceImageStream | java.io.InputStream | सिग्नेचर अपीयरेंस इमेज स्ट्रीम |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


प्रमाणपत्र स्ट्रीम और इमेज फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | डिजिटल सर्टिफिकेट स्ट्रीम |
|
|  | imageFilePath | java.lang.String | सिग्नेचर अपीयरेंस इमेज फ़ाइल पाथ |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


प्रमाणपत्र स्ट्रीम और इमेज स्ट्रीम के साथ DigitalSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | डिजिटल सर्टिफिकेट स्ट्रीम |
|
|  | appearenceImageStream | java.io.InputStream | सिग्नेचर अपीयरेंस इमेज स्ट्रीम |
|

### getReason() {#getReason--}
```
public final String getReason()
```


हस्ताक्षर का कारण प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


हस्ताक्षर का कारण प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


हस्ताक्षर संपर्क को प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


हस्ताक्षर संपर्क को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


हस्ताक्षर स्थान को प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


हस्ताक्षर स्थान को प्राप्त करता है या सेट करता है।


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

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


डॉक्यूमेंट डिजिटल सिग्नेचर की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है।


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


डॉक्यूमेंट डिजिटल सिग्नेचर की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


डिजिटल सर्टिफिकेट फ़ाइल पाथ को प्राप्त करता है या सेट करता है।
यह प्रॉपर्टी केवल तब उपयोग की जाती है जब CertificateStream निर्दिष्ट नहीं किया गया हो।


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


डिजिटल सर्टिफिकेट फ़ाइल GUID को प्राप्त करता है या सेट करता है।
यह प्रॉपर्टी केवल तब उपयोग की जाती है जब CertificateStream निर्दिष्ट नहीं किया गया हो।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


डिजिटल सर्टिफिकेट स्ट्रीम को प्राप्त करता है या सेट करता है।
यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा CertificateGuid के बजाय उपयोग की जाती है।


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


डिजिटल सर्टिफिकेट स्ट्रीम को प्राप्त करता है या सेट करता है।
यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा CertificateGuid के बजाय उपयोग की जाती है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


सिग्नेचर की विज़िबिलिटी को प्राप्त करता है या सेट करता है।


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


सिग्नेचर की विज़िबिलिटी को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


LTV (Long Term Validation) वैलिडेशन फ़्लैग को प्राप्त/सेट करता है।


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


LTV (Long Term Validation) वैलिडेशन फ़्लैग को प्राप्त/सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


कस्टम हैश-साइनिंग इम्प्लीमेंटेशन को प्राप्त करता है या सेट करता है, जिससे कॉलर्स अपने स्वयं के
डिजिटल साइनिंग लॉजिक (HSM, रिमोट साइनर, सॉफ्टवेयर कीस्टोर, आदि)।


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


कस्टम हैश-साइनिंग इम्प्लीमेंटेशन सेट करता है, जिससे कॉलर्स अपने स्वयं के
डिजिटल साइनिंग लॉजिक।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES प्रकार
XAdESType
. डिफ़ॉल्ट मान None है (XAdES बंद है)।
वर्तमान में XAdES सिग्नेचर टाइप केवल .NET Framework के तहत स्प्रेडशीट डॉक्यूमेंट्स के लिए समर्थित है ( .NET Standard के तहत नहीं)।


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES प्रकार
XAdESType
. डिफ़ॉल्ट मान None है (XAdES बंद है)।
वर्तमान में XAdES सिग्नेचर टाइप केवल .NET Framework के तहत स्प्रेडशीट डॉक्यूमेंट्स के लिए समर्थित है ( .NET Standard के तहत नहीं)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
