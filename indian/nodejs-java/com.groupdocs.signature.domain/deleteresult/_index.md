---
title: "DeleteResult"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ से हस्ताक्षरों के हटाने का परिणाम।"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

दस्तावेज़ से हस्ताक्षर (ओं) को हटाने का परिणाम।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | प्रक्रिया के निष्पादन समय को मिलीसेकंड में लौटाता है। |
| [getTotalSignatures()](#getTotalSignatures--) | कुल प्रोसेस किए गए हस्ताक्षरों को लौटाता है। |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | स्रोत दस्तावेज़ का आकार लौटाता है। |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | अपडेटेड दस्तावेज़ का आकार लौटाता है। |
| [getSucceeded()](#getSucceeded--) | सफलतापूर्वक हटाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | न हटाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


प्रक्रिया के निष्पादन समय को मिलीसेकंड में लौटाता है।

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


कुल प्रोसेस किए गए हस्ताक्षरों को लौटाता है।

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


स्रोत दस्तावेज़ का आकार लौटाता है।

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


अपडेटेड दस्तावेज़ का आकार लौटाता है।

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


सफलतापूर्वक हटाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


न हटाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
