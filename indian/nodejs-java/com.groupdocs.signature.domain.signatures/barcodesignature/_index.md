---
title: "BarcodeSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "Barcode Signature गुणों को शामिल करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Barcode Signature गुणों को शामिल करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | सर्च प्रक्रिया के बाद प्राप्त सिग्नेचर पहचानकर्ता के साथ BarcodeSignature ऑब्जेक्ट को इनिशियलाइज़ करें। |
| [BarcodeSignature()](#BarcodeSignature--) | डिफ़ॉल्ट पैरामीटर के साथ BarcodeSignature को इनिशियलाइज़ करें। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Barcode एन्कोड प्रकार निर्दिष्ट करता है। |
| [getText()](#getText--) | Barcode का टेक्स्ट निर्दिष्ट करता है। |
| [getFormat()](#getFormat--) | Barcode सिग्नेचर इमेज का फ़ॉर्मेट निर्दिष्ट करता है। |
| [getContent()](#getContent--) | फ़ॉर्मेट प्रकार की Barcode बाइनरी डेटा इमेज कंटेंट निर्दिष्ट करता है (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [deepClone()](#deepClone--) | Barcode Signature इंस्टेंस को क्लोन करें। |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


सर्च प्रक्रिया के बाद प्राप्त सिग्नेचर पहचानकर्ता के साथ BarcodeSignature ऑब्जेक्ट को इनिशियलाइज़ करें। यह अनूठा पहचानकर्ता इस सिग्नेचर के लिए अतिरिक्त प्रॉपर्टीज़ को दस्तावेज़ सिग्नेचर जानकारी लेयर से खोजने के लिए उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureId | java.lang.String | Signature क्लास की Sign या Search विधि द्वारा प्राप्त अद्वितीय हस्ताक्षर पहचानकर्ता [Signature](../../com.groupdocs.signature/signature). |

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


डिफ़ॉल्ट पैरामीटर के साथ BarcodeSignature को इनिशियलाइज़ करें।

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Barcode एन्कोड प्रकार निर्दिष्ट करता है।

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Barcode का टेक्स्ट निर्दिष्ट करता है।

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Barcode सिग्नेचर इमेज का फ़ॉर्मेट निर्दिष्ट करता है।

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


फ़ॉर्मेट प्रकार की Barcode बाइनरी डेटा इमेज कंटेंट निर्दिष्ट करता है (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). डिफ़ॉल्ट रूप से यह प्रॉपर्टी सेट नहीं होगी। इस फीचर को सक्षम करने के लिए प्रॉपर्टी BarcodeSearchOptions.ReturnContent ([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions\#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions\#setReturnContent-boolean-)) का उपयोग करें।

**Returns:**
byte[]
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


Barcode Signature इंस्टेंस को क्लोन करें।

**Returns:**
java.lang.Object - क्लोन किया गया Barcode Signature इंस्टेंस लौटाता है।
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| छवि | java.awt.image.BufferedImage |  |

