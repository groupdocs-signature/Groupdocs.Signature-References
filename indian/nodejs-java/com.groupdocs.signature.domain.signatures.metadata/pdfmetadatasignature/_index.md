---
title: "PdfMetadataSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "Pdf Metadata हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Pdf Metadata हस्ताक्षर गुण शामिल हैं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | पूर्वनिर्धारित नाम और खाली मान के साथ Pdf Metadata हस्ताक्षर बनाता है |
| [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | पूर्वनिर्धारित मानों के साथ Pdf Metadata हस्ताक्षर बनाता है |
| [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | पूर्वनिर्धारित मानों के साथ Pdf Metadata हस्ताक्षर बनाता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getTagPrefix()](#getTagPrefix--) | Pdf Metadata हस्ताक्षर नाम का उपसर्ग टैग। |
| [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Pdf Metadata हस्ताक्षर नाम का उपसर्ग टैग। |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [deepClone()](#deepClone--) | Metadata Signature इंस्टेंस को क्लोन करें। |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | दिए गए मान के साथ Pdf Metadata Signature इंस्टेंस को क्लोन करें। |
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


पूर्वनिर्धारित नाम और खाली मान के साथ Pdf Metadata हस्ताक्षर बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | Pdf Metadata हस्ताक्षर नाम |

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


पूर्वनिर्धारित मानों के साथ Pdf Metadata हस्ताक्षर बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | Metadata हस्ताक्षर ऑब्जेक्ट का नाम |
| मान | java.lang.Object | Metadata हस्ताक्षर का मान |

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


पूर्वनिर्धारित मानों के साथ Pdf Metadata हस्ताक्षर बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | Metadata हस्ताक्षर ऑब्जेक्ट का नाम |
| मान | java.lang.Object | Metadata हस्ताक्षर का मान |
| टैग | java.lang.String | Metadata हस्ताक्षर का प्रीफ़िक्स टैग |

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Pdf Metadata हस्ताक्षर नाम का उपसर्ग टैग। डिफ़ॉल्ट रूप से यह गुण "xmp" पर सेट है। संभावित मान हैं

**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Pdf Metadata हस्ताक्षर नाम का उपसर्ग टैग। डिफ़ॉल्ट रूप से यह गुण "xmp" पर सेट है। संभावित मान हैं

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

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


Metadata Signature इंस्टेंस को क्लोन करें।

**Returns:**
java.lang.Object - क्लोन किए गए Metadata Signature इंस्टेंस को लौटाता है
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


दिए गए मान के साथ Pdf Metadata Signature इंस्टेंस को क्लोन करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object | नए क्लोन किए गए ऑब्जेक्ट के लिए मान। |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
