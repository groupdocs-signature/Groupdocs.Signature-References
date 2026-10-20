---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "QR-Code हस्ताक्षरों के लिए सारभूत खोज विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

QR-Code हस्ताक्षरों के लिए सारभूत खोज विकल्पों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | डिफ़ॉल्ट मानों के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | एन्कोड टाइप मान के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | एन्कोड टाइप और टेक्स्ट मानों के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QR कोड खोजने के लिए Encode Type प्रॉपर्टी निर्दिष्ट करता है। |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR कोड खोजने के लिए Encode Type प्रॉपर्टी निर्दिष्ट करता है। |
|
|  | [getText()](#getText--) | यदि इसे खोजा और मिलाया जाना चाहिए तो QR-Code सिग्नेचर टेक्स्ट निर्दिष्ट करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | यदि इसे खोजा और मिलाया जाना चाहिए तो QR-Code सिग्नेचर टेक्स्ट निर्दिष्ट करता है। |
|
|  | [getMatchType()](#getMatchType--) | QR-Code टेक्स्ट मैच टाइप खोज को प्राप्त करता है या सेट करता है। |
|
|  | [setMatchType(int value)](#setMatchType-int-) | QR-Code टेक्स्ट मैच टाइप खोज को प्राप्त करता है या सेट करता है। |
|
|  | [getDataEncryption()](#getDataEncryption--) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है। |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है। |
|
|  | [getReturnContent()](#getReturnContent--) | दस्तावेज़ पृष्ठ पर सिग्नेचर की QR-Code इमेज कंटेंट को प्राप्त करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | दस्तावेज़ पृष्ठ पर सिग्नेचर की QR-Code इमेज कंटेंट को प्राप्त करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। |
|
|  | [getReturnContentType()](#getReturnContentType--) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR-Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR-Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


डिफ़ॉल्ट मानों के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


एन्कोड टाइप मान के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QR-Code एन्कोड टाइप निर्दिष्ट करता है। |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


एन्कोड टाइप और टेक्स्ट मानों के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QR-Code एन्कोड टाइप निर्दिष्ट करता है। |
|
|  | पाठ | java.lang.String | QR-Code सिग्नेचर का टेक्स्ट सेट करें। |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR कोड खोजने के लिए Encode Type प्रॉपर्टी निर्दिष्ट करता है।
यदि यह मान सेट नहीं है, तो सभी समर्थित QR-Code प्रकारों के लिए खोज प्रक्रिया की जाती है।


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QR कोड खोजने के लिए Encode Type प्रॉपर्टी निर्दिष्ट करता है।
यदि यह मान सेट नहीं है, तो सभी समर्थित QR-Code प्रकारों के लिए खोज प्रक्रिया की जाती है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


यदि इसे खोजा और मिलाया जाना चाहिए तो QR-Code सिग्नेचर टेक्स्ट निर्दिष्ट करता है।


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


यदि इसे खोजा और मिलाया जाना चाहिए तो QR-Code सिग्नेचर टेक्स्ट निर्दिष्ट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


QR-Code टेक्स्ट मैच टाइप खोज को प्राप्त करता है या सेट करता है। यह केवल तब उपयोग किया जाता है जब Text प्रॉपर्टी सेट हो।


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


QR-Code टेक्स्ट मैच टाइप खोज को प्राप्त करता है या सेट करता है। यह केवल तब उपयोग किया जाता है जब Text प्रॉपर्टी सेट हो।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है।


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


दस्तावेज़ पृष्ठ पर सिग्नेचर की QR-Code इमेज कंटेंट को प्राप्त करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है।
यदि यह फ़्लैग true सेट किया जाता है, तो QR-Code हस्ताक्षर छवि सामग्री आवश्यक फ़ॉर्मेट द्वारा कच्चा इमेज डेटा रखेगी।
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
डिफ़ॉल्ट रूप से यह विकल्प अक्षम है।


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


दस्तावेज़ पृष्ठ पर सिग्नेचर की QR-Code इमेज कंटेंट को प्राप्त करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है।
यदि यह फ़्लैग true सेट किया जाता है, तो QR-Code हस्ताक्षर छवि सामग्री आवश्यक फ़ॉर्मेट द्वारा कच्चा इमेज डेटा रखेगी।
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
डिफ़ॉल्ट रूप से यह विकल्प अक्षम है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR-Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है।
डिफ़ॉल्ट रूप से यह Null पर सेट है। इसका मतलब है कि QR-Code छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी।
यह इमेज फ़ॉर्मेट यहाँ निर्दिष्ट किया गया है
QrCodeSignature.Format
()
संभव समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP।
यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो मूल .png में QR-Code इमेज कंटेंट वापस किया जाएगा।


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR-Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है।
डिफ़ॉल्ट रूप से यह Null पर सेट है। इसका मतलब है कि QR-Code छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी।
यह इमेज फ़ॉर्मेट यहाँ निर्दिष्ट किया गया है
QrCodeSignature.Format
()
संभव समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP।
यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो मूल .png में QR-Code इमेज कंटेंट वापस किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

