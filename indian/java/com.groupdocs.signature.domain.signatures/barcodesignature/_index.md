---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "Barcode सिग्नेचर गुणों को शामिल करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Barcode सिग्नेचर गुणों को शामिल करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | सर्च प्रक्रिया के बाद प्राप्त सिग्नेचर पहचानकर्ता के साथ BarcodeSignature ऑब्जेक्ट को इनिशियलाइज़ करें। |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | डिफ़ॉल्ट पैरामीटरों के साथ BarcodeSignature को इनिशियलाइज़ करें। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | बारकोड एन्कोड प्रकार को निर्दिष्ट करता है। |
|
|  | [getText()](#getText--) | बारकोड का टेक्स्ट निर्दिष्ट करता है। |
|
|  | [getFormat()](#getFormat--) | बारकोड सिग्नेचर छवि का फ़ॉर्मेट निर्दिष्ट करता है। |
|
|  | [getContent()](#getContent--) | बारकोड बाइनरी डेटा छवि सामग्री का प्रकार निर्दिष्ट करता है। |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
|  | [deepClone()](#deepClone--) | Barcode Signature इंस्टेंस को क्लोन करें। |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


सर्च प्रक्रिया के बाद प्राप्त सिग्नेचर पहचानकर्ता के साथ BarcodeSignature ऑब्जेक्ट को इनिशियलाइज़ करें।
इस अद्वितीय पहचानकर्ता का उपयोग दस्तावेज़ हस्ताक्षर सूचना परत से इस हस्ताक्षर के अतिरिक्त गुण खोजने के लिए किया जाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | signatureId | java.lang.String | Signature क्लास के साइन या सर्च मेथड द्वारा प्राप्त अद्वितीय हस्ताक्षर पहचानकर्ता [Signature](../../com.groupdocs.signature/signature). |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


डिफ़ॉल्ट पैरामीटरों के साथ BarcodeSignature को इनिशियलाइज़ करें।


### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


बारकोड एन्कोड प्रकार को निर्दिष्ट करता है।


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


बारकोड का टेक्स्ट निर्दिष्ट करता है।


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


बारकोड सिग्नेचर छवि का फ़ॉर्मेट निर्दिष्ट करता है।


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


बारकोड बाइनरी डेटा छवि सामग्री का प्रकार निर्दिष्ट करता है।
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
डिफ़ॉल्ट रूप से यह गुण सेट नहीं होगा।
गुण का उपयोग करें
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) इस सुविधा को सक्षम करने के लिए।


**Returns:**
byte[]
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

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| छवि | java.awt.image.BufferedImage |  |

