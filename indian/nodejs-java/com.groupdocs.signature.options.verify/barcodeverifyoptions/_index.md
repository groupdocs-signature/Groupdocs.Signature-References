---
title: "BarcodeVerifyOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "बारकोड सत्यापन विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

बारकोड सत्यापन विकल्पों का प्रतिनिधित्व करता है।

--------------------

 **Learn more**  **Learn more**

 *  Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ][How to eVerification Barcode signatures in a document]
 *  Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings


[How to eVerification Barcode signatures in a document]: https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | बारकोड सिग्नेचर के लिए डिफ़ॉल्ट वैरिफिकेशन ऑप्शन बनाता है। |
| [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | सत्यापन टेक्स्ट के साथ डिफ़ॉल्ट वैरिफिकेशन ऑप्शन बनाता है। |
| [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | बारकोड टाइप सत्यापन के साथ डिफ़ॉल्ट वैरिफिकेशन ऑप्शन बनाता है। |
| [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | बारकोड टाइप सत्यापन और टेक्स्ट के साथ डिफ़ॉल्ट वैरिफिकेशन ऑप्शन बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | बारकोड टाइप सत्यापन को प्राप्त करता है या सेट करता है। |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | बारकोड टाइप सत्यापन को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) | स्ट्रिंग में रूपांतरण को ओवरराइड करता है। |
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


बारकोड सिग्नेचर के लिए डिफ़ॉल्ट वैरिफिकेशन ऑप्शन बनाता है।

### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


सत्यापन टेक्स्ट के साथ डिफ़ॉल्ट वैरिफिकेशन ऑप्शन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | सत्यापित करने के लिए बारकोड टेक्स्ट |

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


बारकोड टाइप सत्यापन के साथ डिफ़ॉल्ट वैरिफिकेशन ऑप्शन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | बारकोड टाइप सत्यापन |

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


बारकोड टाइप सत्यापन और टेक्स्ट के साथ डिफ़ॉल्ट वैरिफिकेशन ऑप्शन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | सत्यापित करने के लिए बारकोड टेक्स्ट |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | बारकोड टाइप सत्यापन |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


बारकोड टाइप सत्यापन को प्राप्त करता है या सेट करता है।

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


बारकोड टाइप सत्यापन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग में रूपांतरण को ओवरराइड करता है।

**Returns:**
java.lang.String -
