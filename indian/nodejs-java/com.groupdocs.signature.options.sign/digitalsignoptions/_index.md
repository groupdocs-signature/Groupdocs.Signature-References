---
title: "DigitalSignOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "डिजिटल हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature.options.sign/digitalsignoptions/
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
| [DigitalSignOptions()](#DigitalSignOptions--) | DigitalSignOptions क्लास का नया इंस्टेंस डिफ़ॉल्ट मानों के साथ इनिशियलाइज़ करता है। |
| [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र फ़ाइल के साथ इनिशियलाइज़ करता है। |
| [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र स्ट्रीम के साथ इनिशियलाइज़ करता है। |
| [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र फ़ाइल और इमेज फ़ाइल के साथ इनिशियलाइज़ करता है। |
| [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र फ़ाइल और इमेज स्ट्रीम के साथ इनिशियलाइज़ करता है। |
| [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र स्ट्रीम और इमेज फ़ाइल के साथ इनिशियलाइज़ करता है। |
| [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र स्ट्रीम और इमेज स्ट्रीम के साथ इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getReason()](#getReason--) | सिग्नेचर का कारण प्राप्त करता है या सेट करता है। |
| [setReason(String value)](#setReason-java.lang.String-) | सिग्नेचर का कारण प्राप्त करता है या सेट करता है। |
| [getContact()](#getContact--) | सिग्नेचर संपर्क प्राप्त करता है या सेट करता है। |
| [setContact(String value)](#setContact-java.lang.String-) | सिग्नेचर संपर्क प्राप्त करता है या सेट करता है। |
| [getLocation()](#getLocation--) | सिग्नेचर स्थान प्राप्त करता है या सेट करता है। |
| [setLocation(String value)](#setLocation-java.lang.String-) | सिग्नेचर स्थान प्राप्त करता है या सेट करता है। |
| [getPassword()](#getPassword--) | डिजिटल प्रमाणपत्र का पासवर्ड प्राप्त करता है या सेट करता है। |
| [setPassword(String value)](#setPassword-java.lang.String-) | डिजिटल प्रमाणपत्र का पासवर्ड प्राप्त करता है या सेट करता है। |
| [getSignature()](#getSignature--) | डॉक्यूमेंट डिजिटल सिग्नेचर की प्रॉपर्टीज़ प्राप्त करता है या सेट करता है। |
| [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | डॉक्यूमेंट डिजिटल सिग्नेचर की प्रॉपर्टीज़ प्राप्त करता है या सेट करता है। |
| [getCertificateFilePath()](#getCertificateFilePath--) | डिजिटल प्रमाणपत्र फ़ाइल पाथ प्राप्त करता है या सेट करता है। |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | डिजिटल प्रमाणपत्र फ़ाइल GUID प्राप्त करता है या सेट करता है। |
| [getCertificateStream()](#getCertificateStream--) | डिजिटल प्रमाणपत्र स्ट्रीम प्राप्त करता है या सेट करता है। |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | डिजिटल प्रमाणपत्र स्ट्रीम प्राप्त करता है या सेट करता है। |
| [getVisible()](#getVisible--) | हस्ताक्षर की दृश्यता प्राप्त करता है या सेट करता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | हस्ताक्षर की दृश्यता प्राप्त करता है या सेट करता है। |
| [getXAdESType()](#getXAdESType--) | XAdES प्रकार  XAdESType . |
| [setXAdESType(int value)](#setXAdESType-int-) | XAdES प्रकार  XAdESType . |
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


DigitalSignOptions क्लास का नया इंस्टेंस डिफ़ॉल्ट मानों के साथ इनिशियलाइज़ करता है।

### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र फ़ाइल के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certificateFilePath | java.lang.String | डिजिटल प्रमाणपत्र फ़ाइल पथ |

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र स्ट्रीम के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certificateStream | java.io.InputStream | डिजिटल प्रमाणपत्र स्ट्रीम |

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र फ़ाइल और इमेज फ़ाइल के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certificateFilePath | java.lang.String | डिजिटल प्रमाणपत्र फ़ाइल पथ |
| imageFilePath | java.lang.String | हस्ताक्षर रूपरेखा छवि फ़ाइल पथ |

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र फ़ाइल और इमेज स्ट्रीम के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certificateFilePath | java.lang.String | डिजिटल प्रमाणपत्र फ़ाइल पथ |
| appearenceImageStream | java.io.InputStream | हस्ताक्षर रूपरेखा छवि स्ट्रीम |

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र स्ट्रीम और इमेज फ़ाइल के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certificateStream | java.io.InputStream | डिजिटल प्रमाणपत्र स्ट्रीम |
| imageFilePath | java.lang.String | हस्ताक्षर रूपरेखा छवि फ़ाइल पथ |

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


DigitalSignOptions क्लास का नया इंस्टेंस प्रमाणपत्र स्ट्रीम और इमेज स्ट्रीम के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certificateStream | java.io.InputStream | डिजिटल प्रमाणपत्र स्ट्रीम |
| appearenceImageStream | java.io.InputStream | हस्ताक्षर रूपरेखा छवि स्ट्रीम |

### getReason() {#getReason--}
```
public final String getReason()
```


सिग्नेचर का कारण प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


सिग्नेचर का कारण प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


सिग्नेचर संपर्क प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


सिग्नेचर संपर्क प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


सिग्नेचर स्थान प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


सिग्नेचर स्थान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


डॉक्यूमेंट डिजिटल सिग्नेचर की प्रॉपर्टीज़ प्राप्त करता है या सेट करता है।

**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


डॉक्यूमेंट डिजिटल सिग्नेचर की प्रॉपर्टीज़ प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


डिजिटल प्रमाणपत्र फ़ाइल पथ प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब उपयोग की जाती है जब CertificateStream निर्दिष्ट नहीं किया गया हो।

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


डिजिटल प्रमाणपत्र फ़ाइल GUID प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब उपयोग की जाती है जब CertificateStream निर्दिष्ट नहीं किया गया हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


डिजिटल प्रमाणपत्र स्ट्रीम प्राप्त करता है या सेट करता है। यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा CertificateGuid के बजाय उपयोग की जाती है।

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


डिजिटल प्रमाणपत्र स्ट्रीम प्राप्त करता है या सेट करता है। यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा CertificateGuid के बजाय उपयोग की जाती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


हस्ताक्षर की दृश्यता प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


हस्ताक्षर की दृश्यता प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES प्रकार  XAdESType . डिफ़ॉल्ट मान None है (XAdES बंद है)। वर्तमान में XAdES हस्ताक्षर प्रकार केवल .NET Framework के तहत स्प्रेडशीट दस्तावेज़ों के लिए समर्थित है ( .NET Standard के तहत नहीं)।

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES प्रकार  XAdESType . डिफ़ॉल्ट मान None है (XAdES बंद है)। वर्तमान में XAdES हस्ताक्षर प्रकार केवल .NET Framework के तहत स्प्रेडशीट दस्तावेज़ों के लिए समर्थित है ( .NET Standard के तहत नहीं)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग रूपांतरण को ओवरराइड करें।

**Returns:**
java.lang.String -
