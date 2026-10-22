---
title: "SearchResult"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "निर्दिष्ट दस्तावेज़ में हस्ताक्षरों की खोज का परिणाम।"
type: docs
weight: 16
url: /hi/nodejs-java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

निर्दिष्ट दस्तावेज़ में हस्ताक्षरों की खोज का परिणाम।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | सर्च प्रक्रिया के निष्पादन समय को मिलीसेकंड में लौटाता है। |
| [getTotalSignatures()](#getTotalSignatures--) | सर्च प्रक्रिया द्वारा प्रोसेस किए गए कुल हस्ताक्षरों को लौटाता है। |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | स्रोत दस्तावेज़ का आकार लौटाता है |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | गंतव्य दस्तावेज़ का आकार लौटाता है। |
| [getSucceeded()](#getSucceeded--) | पाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | सर्च मानदंडों द्वारा सर्च प्रक्रिया में विफल हुए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getSignatures()](#getSignatures--) | पता लगाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | हस्ताक्षरों की सशक्त टाइप वाली सूची में रूपांतरण प्रदान करता है। |
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


सर्च प्रक्रिया के निष्पादन समय को मिलीसेकंड में लौटाता है।

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


सर्च प्रक्रिया द्वारा प्रोसेस किए गए कुल हस्ताक्षरों को लौटाता है।

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


स्रोत दस्तावेज़ का आकार लौटाता है

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


गंतव्य दस्तावेज़ का आकार लौटाता है। सर्च मेथड के लिए यह हमेशा 0 लौटाता है।

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


पाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). यह सूची हमेशा Signatures (\#getSignatures.getSignatures/\#setSignatures(List).setSignatures(List)) प्रॉपर्टी के बराबर होगी।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


सर्च मानदंडों द्वारा सर्च प्रक्रिया में विफल हुए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). वर्तमान संस्करण में समर्थित नहीं है।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


पता लगाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


हस्ताक्षरों की सशक्त टाइप वाली सूची में रूपांतरण प्रदान करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - दिए गए हस्ताक्षर प्रकार की सूची लौटाता है।

T : सूची में हस्ताक्षरों का प्रकार।
### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

