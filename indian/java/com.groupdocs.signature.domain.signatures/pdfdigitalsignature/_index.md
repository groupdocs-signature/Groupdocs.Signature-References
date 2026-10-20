---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "Pdf Digital सिग्नेचर गुणों को शामिल करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Pdf Digital सिग्नेचर गुणों को शामिल करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | कोई प्रमाणपत्र नहीं होने पर Pdf Digital Signature को प्रारंभ करें। |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | निर्दिष्ट प्रमाणपत्र के साथ Pdf Digital Signature बनाएं। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | हस्ताक्षरकर्ता द्वारा प्रदान की गई जानकारी जिससे प्राप्तकर्ता हस्ताक्षरकर्ता से संपर्क कर सके। |
हस्ताक्षर को सत्यापित करने के लिए, उदाहरण के लिए।
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | हस्ताक्षरकर्ता द्वारा प्रदान की गई जानकारी जिससे प्राप्तकर्ता हस्ताक्षरकर्ता से संपर्क कर सके। |
हस्ताक्षर को सत्यापित करने के लिए, उदाहरण के लिए।
|
|  | [getLocation()](#getLocation--) | हस्ताक्षर का CPU होस्ट नाम या भौतिक स्थान। |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | हस्ताक्षर का CPU होस्ट नाम या भौतिक स्थान। |
|
|  | [getReason()](#getReason--) | हस्ताक्षर का कारण, जैसे (I agree\u0420\u0406\u0420\u201a\u0412¦)। |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | हस्ताक्षर का कारण, जैसे (I agree\u0420\u0406\u0420\u201a\u0412¦)। |
|
|  | [getType()](#getType--) | Pdf डिजिटल हस्ताक्षर का प्रकार। |
|
|  | [setType(int value)](#setType-int-) | Pdf डिजिटल हस्ताक्षर का प्रकार। |
|
|  | [getTimeStamp()](#getTimeStamp--) | Pdf डिजिटल हस्ताक्षर के लिए टाइमस्टैम्प। |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Pdf डिजिटल हस्ताक्षर के लिए टाइमस्टैम्प। |
|
|  | [getShowProperties()](#getShowProperties--) | हस्ताक्षर गुणों को दिखाने/छिपाने के लिए बाध्य करें। |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | हस्ताक्षर गुणों को दिखाने/छिपाने के लिए बाध्य करें। |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
|  | [deepClone()](#deepClone--) | Barcode Signature इंस्टेंस को क्लोन करें। |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


कोई प्रमाणपत्र नहीं होने पर Pdf Digital Signature को प्रारंभ करें।


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


निर्दिष्ट प्रमाणपत्र के साथ Pdf Digital Signature बनाएं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | प्रमाणपत्र | java.security.KeyStore | X509 प्रमाणपत्र। |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


हस्ताक्षरकर्ता द्वारा प्रदान की गई जानकारी जिससे प्राप्तकर्ता हस्ताक्षरकर्ता से संपर्क कर सके।
हस्ताक्षर को सत्यापित करने के लिए, उदाहरण के रूप में एक फ़ोन नंबर।


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


हस्ताक्षरकर्ता द्वारा प्रदान की गई जानकारी जिससे प्राप्तकर्ता हस्ताक्षरकर्ता से संपर्क कर सके।
हस्ताक्षर को सत्यापित करने के लिए, उदाहरण के रूप में एक फ़ोन नंबर।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


हस्ताक्षर का CPU होस्ट नाम या भौतिक स्थान।


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


हस्ताक्षर का CPU होस्ट नाम या भौतिक स्थान।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


हस्ताक्षर का कारण, जैसे (I agree\u0420\u0406\u0420\u201a\u0412¦)।


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


हस्ताक्षर का कारण, जैसे (I agree\u0420\u0406\u0420\u201a\u0412¦)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Pdf डिजिटल हस्ताक्षर का प्रकार।


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Pdf डिजिटल हस्ताक्षर का प्रकार।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Pdf डिजिटल हस्ताक्षर के लिए टाइमस्टैम्प।
डिफ़ॉल्ट मान null है।


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Pdf डिजिटल हस्ताक्षर के लिए टाइमस्टैम्प।
डिफ़ॉल्ट मान null है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


हस्ताक्षर गुणों को दिखाने/छिपाने के लिए बाध्य करें। यदि ShowProperties सत्य है तो हस्ताक्षर
फ़ील्ड का पूर्वनिर्धारित स्वरूप है
डिजिटल रूप से हस्ताक्षर किया गया द्वारा {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} तारीख: {Date} कारण: {
Reason
(#getReason.getReason/#setReason(String).setReason(String))}
स्थान: {
Location
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties डिफ़ॉल्ट रूप से सत्य है।


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


हस्ताक्षर गुणों को दिखाने/छिपाने के लिए बाध्य करें। यदि ShowProperties सत्य है तो हस्ताक्षर
फ़ील्ड का पूर्वनिर्धारित स्वरूप है
डिजिटल रूप से हस्ताक्षर किया गया द्वारा {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} तारीख: {Date} कारण: {
Reason
(#getReason.getReason/#setReason(String).setReason(String))}
स्थान: {
Location
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties डिफ़ॉल्ट रूप से सत्य है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | हस्ताक्षर | java.lang.Object | तुलना के लिए हस्ताक्षर ऑब्जेक्ट। |
|

**Returns:**
boolean - true लौटाता है यदि पास किया गया हस्ताक्षर ऑब्जेक्ट समान प्रकार का है और उसकी सभी गुण इस इंस्टेंस के गुणों के बराबर हैं।

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode मेथड को ओवरराइड करता है


**Returns:**
int - हस्ताक्षर हैश कोड

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Barcode Signature इंस्टेंस को क्लोन करें।


**Returns:**
java.lang.Object - क्लोन किया गया बारकोड हस्ताक्षर इंस्टेंस लौटाता है।

