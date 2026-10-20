---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "डिजिटल सिग्नेचर के लिए सिग्नेचर लाइन की उपस्थिति का वर्णन करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

डिजिटल सिग्नेचर के लिए सिग्नेचर लाइन की उपस्थिति का वर्णन करता है।
एक सिग्नेचर लाइन केवल एक डिजिटल सिग्नेचर पर लागू की जा सकती है।
सिग्नेचर लाइन हमेशा पहले पृष्ठ पर होती है।
यह सुविधा .docx, .doc, .odt और .xlsx फ़ाइल फ़ॉर्मेट के लिए उपयोगी हो सकती है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | सिग्नेचर लाइन अपीयरेंस ऑब्जेक्ट बनाता है। |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | निर्दिष्ट मानों (साइनर, शीर्षक, ईमेल) के साथ सिग्नेचर लाइन अपीयरेंस बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSigner()](#getSigner--) | सिग्नेचर लाइन के लिए साइनर का नाम प्राप्त करता है या सेट करता है। |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | सिग्नेचर लाइन के लिए साइनर का नाम प्राप्त करता है या सेट करता है। |
|
|  | [getTitle()](#getTitle--) | सिग्नेचर लाइन के लिए शीर्षक प्राप्त करता है या सेट करता है। |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | सिग्नेचर लाइन के लिए शीर्षक प्राप्त करता है या सेट करता है। |
|
|  | [getEmail()](#getEmail--) | सिग्नेचर लाइन में प्रदर्शित होने वाला ईमेल प्राप्त करता है या सेट करता है। |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | सिग्नेचर लाइन में प्रदर्शित होने वाला ईमेल प्राप्त करता है या सेट करता है। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


सिग्नेचर लाइन अपीयरेंस ऑब्जेक्ट बनाता है।


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


निर्दिष्ट मानों (साइनर, शीर्षक, ईमेल) के साथ सिग्नेचर लाइन अपीयरेंस बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | साइनर | java.lang.String | साइनर नाम। |
|
|  | शीर्षक | java.lang.String | सिग्नेचर शीर्षक। |
|
|  | ईमेल | java.lang.String | लेखक का ईमेल। |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


सिग्नेचर लाइन के लिए साइनर का नाम प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


सिग्नेचर लाइन के लिए साइनर का नाम प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


सिग्नेचर लाइन के लिए शीर्षक प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


सिग्नेचर लाइन के लिए शीर्षक प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


सिग्नेचर लाइन में प्रदर्शित होने वाला ईमेल प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


सिग्नेचर लाइन में प्रदर्शित होने वाला ईमेल प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
