---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "QR-code सिग्नेचर गुणों को शामिल करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

QR-code सिग्नेचर गुणों को शामिल करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | खोज प्रक्रिया के बाद प्राप्त हस्ताक्षर पहचानकर्ता के साथ QrCodeSignature ऑब्जेक्ट को प्रारंभ करें। |
|
| [QrCodeSignature()](#QrCodeSignature--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QR-कोड एन्कोड प्रकार निर्दिष्ट करता है। |
|
|  | [getText()](#getText--) | QR-कोड का पाठ निर्दिष्ट करता है। |
|
|  | [getFormat()](#getFormat--) | QR-कोड हस्ताक्षर छवि का प्रारूप निर्दिष्ट करता है। |
|
|  | [getContent()](#getContent--) | निर्दिष्ट करता है QR-कोड बाइनरी डेटा छवि सामग्री का प्रकार |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | डिसेरियलाइज़ेशन के बाद QR-कोड सिग्नेचर टेक्स्ट से ऑब्जेक्ट प्राप्त करें। |
|
|  | [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | डिसेरियलाइज़ेशन के बाद QR-कोड सिग्नेचर टेक्स्ट से ऑब्जेक्ट प्राप्त करें। |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
|  | [deepClone()](#deepClone--) | QR-कोड सिग्नेचर इंस्टेंस को क्लोन करें। |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


खोज प्रक्रिया के बाद प्राप्त हस्ताक्षर पहचानकर्ता के साथ QrCodeSignature ऑब्जेक्ट को प्रारंभ करें।
इस अद्वितीय पहचानकर्ता का उपयोग दस्तावेज़ हस्ताक्षर सूचना परत से इस हस्ताक्षर के अतिरिक्त गुण खोजने के लिए किया जाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | signatureId | java.lang.String | साइन या खोज विधि द्वारा प्राप्त अद्वितीय हस्ताक्षर पहचानकर्ता। |
|

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR-कोड एन्कोड प्रकार निर्दिष्ट करता है।


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


QR-कोड का पाठ निर्दिष्ट करता है।


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


QR-कोड हस्ताक्षर छवि का प्रारूप निर्दिष्ट करता है।


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


निर्दिष्ट करता है QR-कोड बाइनरी डेटा छवि सामग्री का प्रकार
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
डिफ़ॉल्ट रूप से यह गुण सेट नहीं होगा।
गुण का उपयोग करें
QrCodeSearchOptions.ReturnContent
([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions#setReturnContent-boolean-)) इस सुविधा को सक्षम करने के लिए।


**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


डिसेरियलाइज़ेशन के बाद QR-कोड सिग्नेचर टेक्स्ट से ऑब्जेक्ट प्राप्त करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | java.lang.Class<T> |  |

**Returns:**
T -
T
: QR-कोड टेक्स्ट से डिसेरियलाइज़ करने के लिए ऑब्जेक्ट का प्रकार

### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


डिसेरियलाइज़ेशन के बाद QR-कोड सिग्नेचर टेक्स्ट से ऑब्जेक्ट प्राप्त करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | कस्टम डेटा एन्क्रिप्शन इम्प्लीमेंटेशन सेट करें |


T
: QR-कोड टेक्स्ट से डिसेरियलाइज़ करने के लिए ऑब्जेक्ट का प्रकार
|
| प्रकार | java.lang.Class<T> |  |

**Returns:**
T -
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


QR-कोड सिग्नेचर इंस्टेंस को क्लोन करें।


**Returns:**
java.lang.Object - क्लोन किए गए QR-कोड सिग्नेचर इंस्टेंस को लौटाता है।

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| छवि | java.awt.image.BufferedImage |  |

