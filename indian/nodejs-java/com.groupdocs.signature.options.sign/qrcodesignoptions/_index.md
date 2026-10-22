---
title: "QrCodeSignOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "QR-कोड हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 15
url: /hi/nodejs-java/com.groupdocs.signature.options.sign/qrcodesignoptions/
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
| [QrCodeSignOptions()](#QrCodeSignOptions--) | डिफ़ॉल्ट मानों के साथ QRCodeSignOptions क्लास का नया उदाहरण प्रारंभ करता है। |
| [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | पाठ के साथ QRCodeSignOptions क्लास का नया उदाहरण प्रारंभ करता है। |
| [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | टेक्स्ट के साथ BarcodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | QRCode प्रकार को प्राप्त करता है या सेट करता है। |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QRCode प्रकार को प्राप्त करता है या सेट करता है। |
| [getForeColor()](#getForeColor--) | QR-Code बारों के फ़ोर रंग को प्राप्त करता है या सेट करता है। इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | QR-Code बारों के फ़ोर रंग को प्राप्त करता है या सेट करता है। इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। |
| [setForeColor(String value)](#setForeColor-java.lang.String-) | QR-Code बारों के फ़ोर रंग को प्राप्त करता है या सेट करता है। इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। |
| [getInnerMargins()](#getInnerMargins--) | QRCode तत्वों और परिणाम छवि किनारों के बीच की दूरी को प्राप्त करता है या सेट करता है। |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | QRCode तत्वों और परिणाम छवि किनारों के बीच की दूरी को प्राप्त करता है या सेट करता है। |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | परिणाम QR-code छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है। |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | परिणाम QR-code छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है। |
| [getLogoFilePath()](#getLogoFilePath--) | QR-code लोगो छवि फ़ाइल नाम को प्राप्त करता है या सेट करता है। |
| [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | QR-code लोगो छवि फ़ाइल नाम को प्राप्त करता है या सेट करता है। |
| [getLogoStream()](#getLogoStream--) | QR-code लोगो छवि स्ट्रीम को प्राप्त करता है या सेट करता है। |
| [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | QR-code लोगो छवि स्ट्रीम को प्राप्त करता है या सेट करता है। |
| [getData()](#getData--) | QR-Code सामग्री में क्रमबद्ध करने के लिए कस्टम ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [setData(Object value)](#setData-java.lang.Object-) | QR-Code सामग्री में क्रमबद्ध करने के लिए कस्टम ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [getDataEncryption()](#getDataEncryption--) | QR-Code हस्ताक्षर टेक्स्ट या डेटा गुणों को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को प्राप्त करता है या सेट करता है। |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code हस्ताक्षर टेक्स्ट या डेटा गुणों को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को प्राप्त करता है या सेट करता है। |
| [getReturnContent()](#getReturnContent--) | दस्तावेज़ पृष्ठ पर रखी गई हस्ताक्षर की QR‑Code छवि सामग्री प्राप्त करने के लिए फ़्लैग को प्राप्त या सेट करता है। |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | दस्तावेज़ पृष्ठ पर रखी गई हस्ताक्षर की QR‑Code छवि सामग्री प्राप्त करने के लिए फ़्लैग को प्राप्त या सेट करता है। |
| [getReturnContentType()](#getReturnContentType--) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR‑Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR‑Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


डिफ़ॉल्ट मानों के साथ QRCodeSignOptions क्लास का नया उदाहरण प्रारंभ करता है।

### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


पाठ के साथ QRCodeSignOptions क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | हस्ताक्षर पाठ। |

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


टेक्स्ट के साथ BarcodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | QRCode पाठ |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRCode एन्कोड प्रकार देखें [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QRCode प्रकार को प्राप्त करता है या सेट करता है।

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QRCode प्रकार को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


QR‑Code बारों का फ़ोर रंग प्राप्त या सेट करता है। इस प्रॉपर्टी के उपयोग से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानी से उपयोग करें।

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


QR‑Code बारों का फ़ोर रंग प्राप्त या सेट करता है। इस प्रॉपर्टी के उपयोग से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानी से उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


QR‑Code बारों का फ़ोर रंग प्राप्त या सेट करता है। इस प्रॉपर्टी के उपयोग से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानी से उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


QRCode तत्वों और परिणाम छवि किनारों के बीच की दूरी को प्राप्त करता है या सेट करता है।

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


QRCode तत्वों और परिणाम छवि किनारों के बीच की दूरी को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


परिणामी QR‑code छवि में पाठ का संरेखण प्राप्त या सेट करता है। डिफ़ॉल्ट मान None है।

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


परिणामी QR‑code छवि में पाठ का संरेखण प्राप्त या सेट करता है। डिफ़ॉल्ट मान None है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


QR‑code लोगो छवि फ़ाइल नाम प्राप्त या सेट करता है। यह प्रॉपर्टी केवल तभी उपयोग में है जब LogoStream निर्दिष्ट न हो। इस प्रॉपर्टी के उपयोग से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानी से उपयोग करें।

**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


QR‑code लोगो छवि फ़ाइल नाम प्राप्त या सेट करता है। यह प्रॉपर्टी केवल तभी उपयोग में है जब LogoStream निर्दिष्ट न हो। इस प्रॉपर्टी के उपयोग से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानी से उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


QR‑code लोगो छवि स्ट्रीम प्राप्त या सेट करता है। यदि यह प्रॉपर्टी निर्दिष्ट है तो यह हमेशा LogoGuid के बजाय उपयोग की जाती है। इस प्रॉपर्टी के उपयोग से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानी से उपयोग करें।

**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


QR‑code लोगो छवि स्ट्रीम प्राप्त या सेट करता है। यदि यह प्रॉपर्टी निर्दिष्ट है तो यह हमेशा LogoGuid के बजाय उपयोग की जाती है। इस प्रॉपर्टी के उपयोग से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानी से उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


QR-Code सामग्री में क्रमबद्ध करने के लिए कस्टम ऑब्जेक्ट को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


QR-Code सामग्री में क्रमबद्ध करने के लिए कस्टम ऑब्जेक्ट को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-Code हस्ताक्षर टेक्स्ट या डेटा गुणों को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को प्राप्त करता है या सेट करता है।

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-Code हस्ताक्षर टेक्स्ट या डेटा गुणों को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


दस्तावेज़ पृष्ठ पर रखे गए हस्ताक्षर की QR‑Code छवि सामग्री प्राप्त करने के लिए फ़्लैग को प्राप्त या सेट करता है। यदि यह फ़्लैग true पर सेट किया जाता है, तो QR‑Code हस्ताक्षर छवि सामग्री आवश्यक फ़ॉर्मेट ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)) द्वारा कच्चा इमेज डेटा रखेगी। डिफ़ॉल्ट रूप से यह विकल्प अक्षम है।

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


दस्तावेज़ पृष्ठ पर रखे गए हस्ताक्षर की QR‑Code छवि सामग्री प्राप्त करने के लिए फ़्लैग को प्राप्त या सेट करता है। यदि यह फ़्लैग true पर सेट किया जाता है, तो QR‑Code हस्ताक्षर छवि सामग्री आवश्यक फ़ॉर्मेट ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)) द्वारा कच्चा इमेज डेटा रखेगी। डिफ़ॉल्ट रूप से यह विकल्प अक्षम है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR‑Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से इसे Null पर सेट किया जाता है। इसका अर्थ है कि QR‑Code छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी। यह छवि फ़ॉर्मेट QrCodeSignature.Format पर निर्दिष्ट है ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\\#getFormat)/\\{@link QrCodeSignature\\#(FileType)\\})। संभव समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो QR‑Code छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


जब ReturnContent प्रॉपर्टी सक्षम हो, तो QR‑Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से इसे Null पर सेट किया जाता है। इसका अर्थ है कि QR‑Code छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी। यह छवि फ़ॉर्मेट QrCodeSignature.Format पर निर्दिष्ट है ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\\#getFormat)/\\{@link QrCodeSignature\\#(FileType)\\})। संभव समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो QR‑Code छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग रूपांतरण को ओवरराइड करें।

**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
