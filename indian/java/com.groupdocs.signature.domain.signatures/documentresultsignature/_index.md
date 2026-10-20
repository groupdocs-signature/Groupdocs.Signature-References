---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "नए बनाए गए सिग्नेचर वाले दस्तावेज़ के लिए आर्काइव दस्तावेज़ साइनिंग प्रक्रिया के प्रोसेसिंग परिणाम।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

नए बनाए गए सिग्नेचर वाले दस्तावेज़ के लिए आर्काइव दस्तावेज़ साइनिंग प्रक्रिया के प्रोसेसिंग परिणाम।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFileName()](#getFileName--) | दस्तावेज़ फ़ाइल नाम |
|
|  | [getProcessingTime()](#getProcessingTime--) | प्रक्रिया के निष्पादन समय को मिलीसेकंड में लौटाता है |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | कुल प्रोसेस किए गए हस्ताक्षर लौटाता है |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | स्रोत दस्तावेज़ का आकार लौटाता है |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | गंतव्य दस्तावेज़ का आकार लौटाता है |
|
|  | [getSucceeded()](#getSucceeded--) | सफलतापूर्वक प्रोसेस किए गए हस्ताक्षर की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | प्रक्रिया के दौरान विफल हुए हस्ताक्षर की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | यदि दस्तावेज़ त्रुटि के साथ प्रोसेस किया गया, तो यह प्रॉपर्टी त्रुटि संदेश रखेगी |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


दस्तावेज़ फ़ाइल नाम


**Returns:**
java.lang.String
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


प्रक्रिया के निष्पादन समय को मिलीसेकंड में लौटाता है


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


कुल प्रोसेस किए गए हस्ताक्षर लौटाता है


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


गंतव्य दस्तावेज़ का आकार लौटाता है


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


सफलतापूर्वक प्रोसेस किए गए हस्ताक्षर की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


प्रक्रिया के दौरान विफल हुए हस्ताक्षर की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


यदि दस्तावेज़ त्रुटि के साथ प्रोसेस किया गया, तो यह प्रॉपर्टी त्रुटि संदेश रखेगी


**Returns:**
java.lang.String
