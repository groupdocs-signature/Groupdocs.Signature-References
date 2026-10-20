---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "QR-कोड हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

QR-कोड हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | डिफ़ॉल्ट मानों के साथ QRCodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | टेक्स्ट के साथ QRCodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | पाठ के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QR कोड प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR कोड प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [getForeColor()](#getForeColor--) | QR-Code बारों का फ़ोर रंग प्राप्त करता है या सेट करता है |
इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं।
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | QR-Code बारों का फ़ोर रंग प्राप्त करता है या सेट करता है |
इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं।
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | QR-Code बारों का फ़ोर रंग प्राप्त करता है या सेट करता है |
इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं।
|
|  | [getInnerMargins()](#getInnerMargins--) | QRCode तत्वों और परिणाम छवि सीमाओं के बीच की जगह प्राप्त करता है या सेट करता है। |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | QRCode तत्वों और परिणाम छवि सीमाओं के बीच की जगह प्राप्त करता है या सेट करता है। |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | परिणाम QR-code छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है। |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | परिणाम QR-code छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है। |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | QR-code लोगो छवि फ़ाइल नाम प्राप्त करता है या सेट करता है। |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | QR-code लोगो छवि फ़ाइल नाम प्राप्त करता है या सेट करता है। |
|
|  | [getLogoStream()](#getLogoStream--) | QR-code लोगो छवि स्ट्रीम प्राप्त करता है या सेट करता है। |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | QR-code लोगो छवि स्ट्रीम प्राप्त करता है या सेट करता है। |
|
|  | [getData()](#getData--) | QR-Code सामग्री में क्रमबद्ध करने के लिए कस्टम ऑब्जेक्ट प्राप्त करता है या सेट करता है। |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | QR-Code सामग्री में क्रमबद्ध करने के लिए कस्टम ऑब्जेक्ट प्राप्त करता है या सेट करता है। |
|
|  | [getDataEncryption()](#getDataEncryption--) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है। |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है। |
|
|  | [getReturnContent()](#getReturnContent--) | दस्तावेज़ पृष्ठ पर रखी गई हस्ताक्षर की QR-Code छवि सामग्री प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | दस्तावेज़ पृष्ठ पर रखी गई हस्ताक्षर की QR-Code छवि सामग्री प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
|
|  | [getReturnContentType()](#getReturnContentType--) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR-Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR-Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


डिफ़ॉल्ट मानों के साथ QRCodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


टेक्स्ट के साथ QRCodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | हस्ताक्षर टेक्स्ट। |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


पाठ के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | QRCode टेक्स्ट |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRCode एन्कोड प्रकार देखें [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR कोड प्रकार को प्राप्त करता है या सेट करता है।


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QR कोड प्रकार को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


QR-Code बारों का फ़ोर रंग प्राप्त करता है या सेट करता है
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


QR-Code बारों का फ़ोर रंग प्राप्त करता है या सेट करता है
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


QR-Code बारों का फ़ोर रंग प्राप्त करता है या सेट करता है
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


QRCode तत्वों और परिणाम छवि सीमाओं के बीच की जगह प्राप्त करता है या सेट करता है।


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


QRCode तत्वों और परिणाम छवि सीमाओं के बीच की जगह प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


परिणाम QR-code छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान None है।


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


परिणाम QR-code छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान None है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


QR-code लोगो छवि फ़ाइल नाम प्राप्त करता है या सेट करता है।
यह प्रॉपर्टी केवल तब उपयोग में है जब LogoStream निर्दिष्ट नहीं किया गया हो।
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


QR-code लोगो छवि फ़ाइल नाम प्राप्त करता है या सेट करता है।
यह प्रॉपर्टी केवल तब उपयोग में है जब LogoStream निर्दिष्ट नहीं किया गया हो।
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


QR-code लोगो छवि स्ट्रीम प्राप्त करता है या सेट करता है।
यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा LogoGuid के बजाय उपयोग की जाती है।
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


QR-code लोगो छवि स्ट्रीम प्राप्त करता है या सेट करता है।
यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा LogoGuid के बजाय उपयोग की जाती है।
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


QR-Code सामग्री में क्रमबद्ध करने के लिए कस्टम ऑब्जेक्ट प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


QR-Code सामग्री में क्रमबद्ध करने के लिए कस्टम ऑब्जेक्ट प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

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


दस्तावेज़ पृष्ठ पर रखी गई हस्ताक्षर की QR-Code छवि सामग्री प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है।
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


दस्तावेज़ पृष्ठ पर रखी गई हस्ताक्षर की QR-Code छवि सामग्री प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है।
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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
संभव समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP।
यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो QR-Code छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।


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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
संभव समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP।
यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो QR-Code छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
