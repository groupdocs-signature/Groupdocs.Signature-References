---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "बारकोड हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

बारकोड हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | डिफ़ॉल्ट मानों के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है। |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | पाठ के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है। |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | पाठ के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | बारकोड प्रकार प्राप्त करता है या सेट करता है। |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | बारकोड प्रकार प्राप्त करता है या सेट करता है। |
|
|  | [getForeColor()](#getForeColor--) | बारकोड बारों का अग्र रंग प्राप्त करता है या सेट करता है |
इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं।
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | बारकोड बारों का अग्र रंग प्राप्त करता है या सेट करता है |
इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं।
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | बारकोड बारों का अग्र रंग प्राप्त करता है या सेट करता है |
इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं।
|
|  | [getInnerMargins()](#getInnerMargins--) | बारकोड तत्वों और परिणाम छवि सीमाओं के बीच की दूरी प्राप्त करता है या सेट करता है। |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | बारकोड तत्वों और परिणाम छवि सीमाओं के बीच की दूरी प्राप्त करता है या सेट करता है। |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | परिणाम बारकोड छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है। |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | परिणाम बारकोड छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है। |
|
|  | [getReturnContent()](#getReturnContent--) | दस्तावेज़ पृष्ठ पर रखे गए हस्ताक्षर की बारकोड छवि सामग्री प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | दस्तावेज़ पृष्ठ पर रखे गए हस्ताक्षर की बारकोड छवि सामग्री प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
|
|  | [getReturnContentType()](#getReturnContentType--) | जब ReturnContent प्रॉपर्टी सक्षम हो, तब बारकोड हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | जब ReturnContent प्रॉपर्टी सक्षम हो, तब बारकोड हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
|
|  | [validate()](#validate--) | बारकोड विकल्प पैरामीटरों को मान्य करने के लिए आंतरिक विधि। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


डिफ़ॉल्ट मानों के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है।


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


पाठ के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | बारकोड टेक्स्ट |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


पाठ के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | बारकोड टेक्स्ट |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | बारकोड एन्कोड प्रकार देखें [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


बारकोड प्रकार प्राप्त करता है या सेट करता है।


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


बारकोड प्रकार प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


बारकोड बारों का अग्र रंग प्राप्त करता है या सेट करता है
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


बारकोड बारों का अग्र रंग प्राप्त करता है या सेट करता है
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


बारकोड बारों का अग्र रंग प्राप्त करता है या सेट करता है
इस प्रॉपर्टी का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। इसे सावधानीपूर्वक उपयोग करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


बारकोड तत्वों और परिणाम छवि सीमाओं के बीच की दूरी प्राप्त करता है या सेट करता है।


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


बारकोड तत्वों और परिणाम छवि सीमाओं के बीच की दूरी प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


परिणाम बारकोड छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान None है।


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


परिणाम बारकोड छवि में पाठ के संरेखण को प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान None है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


दस्तावेज़ पृष्ठ पर रखे गए हस्ताक्षर की बारकोड छवि सामग्री प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है।
यदि यह फ़्लैग true सेट किया जाता है, तो बारकोड हस्ताक्षर छवि सामग्री आवश्यक फ़ॉर्मेट में कच्चा इमेज डेटा रखेगी।
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
डिफ़ॉल्ट रूप से यह विकल्प अक्षम है।


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


दस्तावेज़ पृष्ठ पर रखे गए हस्ताक्षर की बारकोड छवि सामग्री प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है।
यदि यह फ़्लैग true सेट किया जाता है, तो बारकोड हस्ताक्षर छवि सामग्री आवश्यक फ़ॉर्मेट में कच्चा इमेज डेटा रखेगी।
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


जब ReturnContent प्रॉपर्टी सक्षम हो, तब बारकोड हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है।
डिफ़ॉल्ट रूप से इसे Null पर सेट किया गया है। इसका अर्थ है कि बारकोड छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी।
यह इमेज फ़ॉर्मेट यहाँ निर्दिष्ट किया गया है
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
संभव समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP।
यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है, तो बारकोड छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


जब ReturnContent प्रॉपर्टी सक्षम हो, तब बारकोड हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है।
डिफ़ॉल्ट रूप से इसे Null पर सेट किया गया है। इसका अर्थ है कि बारकोड छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी।
यह इमेज फ़ॉर्मेट यहाँ निर्दिष्ट किया गया है
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
संभव समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP।
यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है, तो बारकोड छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


बारकोड विकल्प पैरामीटरों को मान्य करने के लिए आंतरिक विधि।


### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
