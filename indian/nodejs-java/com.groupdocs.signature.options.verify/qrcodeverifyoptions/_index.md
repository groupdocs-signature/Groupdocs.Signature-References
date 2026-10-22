---
title: "QrCodeVerifyOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ QR-कोड हस्ताक्षर को सत्यापित करने के विकल्प रखता है।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

दस्तावेज़ QR-कोड हस्ताक्षर को सत्यापित करने के विकल्प रखता है।

--------------------

**Learn more**

 *  Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/
[Advanced usage of eVerification QR-code signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | QR-कोड सिग्नेचर के लिए QRCodeVerifyOptions वैरिफिकेशन ऑप्शन बनाता है। |
| [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | QR-कोड सिग्नेचर के लिए QRCodeVerifyOptions वैरिफिकेशन ऑप्शन बनाता है जिसमें सत्यापित करने के लिए QR-कोड टेक्स्ट शामिल है। |
| [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR-कोड सिग्नेचर के लिए QRCodeVerifyOptions वैरिफिकेशन ऑप्शन बनाता है जिसमें टेक्स्ट और सत्यापित करने के लिए QR-कोड एन्कोड टाइप शामिल है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | QR-कोड टाइप सत्यापन को प्राप्त करता है या सेट करता है। |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR-कोड टाइप सत्यापन को प्राप्त करता है या सेट करता है। |
| [getDataEncryption()](#getDataEncryption--) | QR-कोड सिग्नेचर टेक्स्ट प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के इम्प्लीमेंटेशन को प्राप्त करता है या सेट करता है। |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-कोड सिग्नेचर टेक्स्ट प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के इम्प्लीमेंटेशन को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) | स्ट्रिंग में रूपांतरण को ओवरराइड करता है। |
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


QR-कोड सिग्नेचर के लिए QRCodeVerifyOptions वैरिफिकेशन ऑप्शन बनाता है।

### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


QR-कोड सिग्नेचर के लिए QRCodeVerifyOptions वैरिफिकेशन ऑप्शन बनाता है जिसमें सत्यापित करने के लिए QR-कोड टेक्स्ट शामिल है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | सत्यापित करने के लिए QR-कोड टेक्स्ट |

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


QR-कोड सिग्नेचर के लिए QRCodeVerifyOptions वैरिफिकेशन ऑप्शन बनाता है जिसमें टेक्स्ट और सत्यापित करने के लिए QR-कोड एन्कोड टाइप शामिल है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | सत्यापित किया जाने वाला पाठ |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | एन्कोडिंग का प्रकार |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR-कोड टाइप सत्यापन को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी वैकल्पिक है।

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QR-कोड टाइप सत्यापन को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी वैकल्पिक है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-कोड सिग्नेचर टेक्स्ट प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के इम्प्लीमेंटेशन को प्राप्त करता है या सेट करता है।

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-कोड सिग्नेचर टेक्स्ट प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के इम्प्लीमेंटेशन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग में रूपांतरण को ओवरराइड करता है।

**Returns:**
java.lang.String -
