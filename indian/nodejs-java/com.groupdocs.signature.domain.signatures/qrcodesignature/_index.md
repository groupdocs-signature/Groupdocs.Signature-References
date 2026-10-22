---
title: "QrCodeSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "QR-code signature गुणों को शामिल करता है।"
type: docs
weight: 16
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

QR-code signature गुणों को शामिल करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | खोज प्रक्रिया के बाद प्राप्त हस्ताक्षर पहचानकर्ता के साथ QrCodeSignature ऑब्जेक्ट को प्रारंभ करें। |
| [QrCodeSignature()](#QrCodeSignature--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | QR-code एन्कोड प्रकार निर्दिष्ट करता है। |
| [getText()](#getText--) | QR-code का पाठ निर्दिष्ट करता है। |
| [getFormat()](#getFormat--) | QR-code हस्ताक्षर छवि का प्रारूप निर्दिष्ट करता है। |
| [getContent()](#getContent--) | प्रकार Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)) के QR-code बाइनरी डेटा छवि सामग्री को निर्दिष्ट करता है। |
| [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | डिसीरियलाइज़ेशन के बाद QR-Code हस्ताक्षर पाठ से ऑब्जेक्ट प्राप्त करें। |
| [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | डिसीरियलाइज़ेशन के बाद QR-Code हस्ताक्षर पाठ से ऑब्जेक्ट प्राप्त करें। |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [deepClone()](#deepClone--) | QR-Code हस्ताक्षर इंस्टेंस को क्लोन करें। |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


खोज प्रक्रिया के बाद प्राप्त हस्ताक्षर पहचानकर्ता के साथ QrCodeSignature ऑब्जेक्ट को प्रारंभ करें। यह अद्वितीय पहचानकर्ता इस हस्ताक्षर के लिए दस्तावेज़ हस्ताक्षर जानकारी परत से अतिरिक्त गुण खोजने के लिए उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureId | java.lang.String | हस्ताक्षर या खोज विधि द्वारा प्राप्त अद्वितीय हस्ताक्षर पहचानकर्ता। |

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR-code एन्कोड प्रकार निर्दिष्ट करता है।

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


QR-code का पाठ निर्दिष्ट करता है।

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


QR-code हस्ताक्षर छवि का प्रारूप निर्दिष्ट करता है।

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


प्रकार Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)) के QR-code बाइनरी डेटा छवि सामग्री को निर्दिष्ट करता है। डिफ़ॉल्ट रूप से यह प्रॉपर्टी सेट नहीं होगी। इस सुविधा को सक्षम करने के लिए QrCodeSearchOptions.ReturnContent प्रॉपर्टी का उपयोग करें ([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#setReturnContent-boolean-))।

**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


डिसीरियलाइज़ेशन के बाद QR-Code हस्ताक्षर पाठ से ऑब्जेक्ट प्राप्त करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रकार | java.lang.Class<T> |  |

**Returns:**
T -  T : QR-Code पाठ से डिसीरियलाइज़ करने के लिए ऑब्जेक्ट का प्रकार
### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


डिसीरियलाइज़ेशन के बाद QR-Code हस्ताक्षर पाठ से ऑब्जेक्ट प्राप्त करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | कस्टम डेटा एन्क्रिप्शन कार्यान्वयन सेट करें |

T : QR-Code पाठ से डिसीरियलाइज़ करने के लिए ऑब्जेक्ट का प्रकार |
| प्रकार | java.lang.Class<T> |  |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| हस्ताक्षर | java.lang.Object | तुलना के लिए हस्ताक्षर ऑब्जेक्ट। |

**Returns:**
boolean - यदि पास किया गया हस्ताक्षर ऑब्जेक्ट समान प्रकार का है और उसकी सभी गुण इस इंस्टेंस की गुणों के बराबर हैं तो true लौटाता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode मेथड को ओवरराइड करता है।

**Returns:**
int - हस्ताक्षर हैश कोड
### deepClone() {#deepClone--}
```
public Object deepClone()
```


QR-Code हस्ताक्षर इंस्टेंस को क्लोन करें।

**Returns:**
java.lang.Object - क्लोन किए गए QR-code हस्ताक्षर इंस्टेंस को लौटाता है।
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| छवि | java.awt.image.BufferedImage |  |

