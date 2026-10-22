---
title: "ImageSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "Image signature गुणों को शामिल करता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Image signature गुणों को शामिल करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | सर्च प्रक्रिया के बाद प्राप्त हस्ताक्षर पहचानकर्ता के साथ ImageSignature ऑब्जेक्ट को इनिशियलाइज़ करें। |
| [ImageSignature()](#ImageSignature--) | डिफ़ॉल्ट पैरामीटर के साथ ImageSignature को इनिशियलाइज़ करें। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSize()](#getSize--) | हस्ताक्षर छवि का आकार बाइट्स में निर्दिष्ट करता है। |
| [setSize(int value)](#setSize-int-) | हस्ताक्षर छवि का आकार बाइट्स में निर्दिष्ट करता है। |
| [getFormat()](#getFormat--) | हस्ताक्षर छवि का फ़ॉर्मेट निर्दिष्ट करता है। |
| [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | हस्ताक्षर छवि का फ़ॉर्मेट निर्दिष्ट करता है। |
| [getContent()](#getContent--) | फ़ॉर्मेट प्रकार की छवि बाइनरी डेटा सामग्री निर्दिष्ट करता है (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [deepClone()](#deepClone--) | Barcode Signature इंस्टेंस को क्लोन करें। |
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


सर्च प्रक्रिया के बाद प्राप्त हस्ताक्षर पहचानकर्ता के साथ ImageSignature ऑब्जेक्ट को प्रारंभ करें। यह अद्वितीय पहचानकर्ता इस हस्ताक्षर के अतिरिक्त गुणों को दस्तावेज़ हस्ताक्षर जानकारी परत से खोजने के लिए उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureId | java.lang.String | Signature क्लास की Sign या Search विधि द्वारा प्राप्त अद्वितीय हस्ताक्षर पहचानकर्ता [Signature](../../com.groupdocs.signature/signature). |

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


डिफ़ॉल्ट पैरामीटर के साथ ImageSignature को इनिशियलाइज़ करें।

### getSize() {#getSize--}
```
public final int getSize()
```


हस्ताक्षर छवि का आकार बाइट्स में निर्दिष्ट करता है।

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


हस्ताक्षर छवि का आकार बाइट्स में निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


हस्ताक्षर छवि का फ़ॉर्मेट निर्दिष्ट करता है।

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


हस्ताक्षर छवि का फ़ॉर्मेट निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


फ़ॉर्मेट प्रकार की छवि बाइनरी डेटा सामग्री निर्दिष्ट करता है (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). डिफ़ॉल्ट रूप से यह प्रॉपर्टी सेट नहीं होगी। इस सुविधा को सक्षम करने के लिए प्रॉपर्टी ImageSearchOptions.ReturnContent (\{ ImageSearchOptions\#getReturnContent\}/\{ ImageSearchOptions\#setReturnContent(boolean)\}) का उपयोग करें।

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
