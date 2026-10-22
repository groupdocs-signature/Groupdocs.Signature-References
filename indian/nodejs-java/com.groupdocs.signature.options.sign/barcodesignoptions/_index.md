---
title: "BarcodeSignOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "Barcode signature विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Barcode signature विकल्पों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [BarcodeSignOptions()](#BarcodeSignOptions--) | डिफ़ॉल्ट मानों के साथ BarcodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | टेक्स्ट के साथ BarcodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | टेक्स्ट के साथ BarcodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Barcode प्रकार को प्राप्त करता है या सेट करता है। |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Barcode प्रकार को प्राप्त करता है या सेट करता है। |
| [getForeColor()](#getForeColor--) | Barcode बारों के फ़ोर रंग को प्राप्त करता है या सेट करता है। इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Barcode बारों के फ़ोर रंग को प्राप्त करता है या सेट करता है। इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। |
| [setForeColor(String value)](#setForeColor-java.lang.String-) | Barcode बारों के फ़ोर रंग को प्राप्त करता है या सेट करता है। इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। |
| [getInnerMargins()](#getInnerMargins--) | Barcode तत्वों और परिणाम छवि की सीमाओं के बीच की दूरी को प्राप्त करता है या सेट करता है। |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Barcode तत्वों और परिणाम छवि की सीमाओं के बीच की दूरी को प्राप्त करता है या सेट करता है। |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | परिणाम Barcode छवि में टेक्स्ट की संरेखण को प्राप्त करता है या सेट करता है। |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | परिणाम Barcode छवि में टेक्स्ट की संरेखण को प्राप्त करता है या सेट करता है। |
| [getReturnContent()](#getReturnContent--) | दस्तावेज़ पृष्ठ पर रखी गई सिग्नेचर की Barcode छवि सामग्री प्राप्त करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | दस्तावेज़ पृष्ठ पर रखी गई सिग्नेचर की Barcode छवि सामग्री प्राप्त करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। |
| [getReturnContentType()](#getReturnContentType--) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो Barcode सिग्नेचर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो Barcode सिग्नेचर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
| [validate()](#validate--) | Barcode विकल्प पैरामीटरों को मान्य करने के लिए आंतरिक मेथड। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


डिफ़ॉल्ट मानों के साथ BarcodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


टेक्स्ट के साथ BarcodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | Barcode टेक्स्ट |

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


टेक्स्ट के साथ BarcodeSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | Barcode टेक्स्ट |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode एन्कोड प्रकार देखें [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Barcode प्रकार को प्राप्त करता है या सेट करता है।

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Barcode प्रकार को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Barcode बारों के फ़ोर रंग को प्राप्त करता है या सेट करता है। इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Barcode बारों के फ़ोर रंग को प्राप्त करता है या सेट करता है। इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Barcode बारों के फ़ोर रंग को प्राप्त करता है या सेट करता है। इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Barcode तत्वों और परिणाम छवि की सीमाओं के बीच की दूरी को प्राप्त करता है या सेट करता है।

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Barcode तत्वों और परिणाम छवि की सीमाओं के बीच की दूरी को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


परिणाम Barcode छवि में टेक्स्ट की संरेखण को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान None है।

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


परिणाम Barcode छवि में टेक्स्ट की संरेखण को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान None है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


दस्तावेज़ पृष्ठ पर रखी गई सिग्नेचर की Barcode छवि सामग्री प्राप्त करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। यदि यह फ़्लैग true पर सेट किया जाता है, तो Barcode सिग्नेचर छवि सामग्री आवश्यक फ़ॉर्मेट ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)) द्वारा कच्चा इमेज डेटा रखेगी। डिफ़ॉल्ट रूप से यह विकल्प निष्क्रिय है।

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


दस्तावेज़ पृष्ठ पर रखी गई सिग्नेचर की Barcode छवि सामग्री प्राप्त करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। यदि यह फ़्लैग true पर सेट किया जाता है, तो Barcode सिग्नेचर छवि सामग्री आवश्यक फ़ॉर्मेट ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)) द्वारा कच्चा इमेज डेटा रखेगी। डिफ़ॉल्ट रूप से यह विकल्प निष्क्रिय है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


जब ReturnContent प्रॉपर्टी सक्षम हो, तो Barcode सिग्नेचर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से इसे Null पर सेट किया गया है। इसका अर्थ है कि Barcode छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी। यह इमेज फ़ॉर्मेट BarcodeSignature.Format पर निर्दिष्ट है ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) संभावित समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो Barcode छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


जब ReturnContent प्रॉपर्टी सक्षम हो, तो Barcode सिग्नेचर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से इसे Null पर सेट किया गया है। इसका अर्थ है कि Barcode छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी। यह इमेज फ़ॉर्मेट BarcodeSignature.Format पर निर्दिष्ट है ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)) संभावित समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो Barcode छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Barcode विकल्प पैरामीटरों को मान्य करने के लिए आंतरिक मेथड।

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग रूपांतरण को ओवरराइड करें।

**Returns:**
java.lang.String -
