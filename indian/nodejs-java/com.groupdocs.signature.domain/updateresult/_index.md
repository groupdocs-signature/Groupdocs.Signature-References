---
title: "UpdateResult"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ में हस्ताक्षरों के संशोधन का परिणाम।"
type: docs
weight: 19
url: /hi/nodejs-java/com.groupdocs.signature.domain/updateresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class UpdateResult implements IResult
```

दस्तावेज़ में हस्ताक्षरों के संशोधन का परिणाम।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | प्रक्रिया के निष्पादन समय को मिलीसेकंड में लौटाता है। |
| [getTotalSignatures()](#getTotalSignatures--) | कुल प्रोसेस किए गए हस्ताक्षरों को लौटाता है। |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | स्रोत दस्तावेज़ का आकार लौटाता है |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | गंतव्य दस्तावेज़ का आकार लौटाता है |
| [getSucceeded()](#getSucceeded--) | सफलतापूर्वक संशोधित किए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | हस्ताक्षरों की सूची जो अपडेट नहीं किए गए [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
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


सफलतापूर्वक संशोधित किए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


हस्ताक्षरों की सूची जो अपडेट नहीं किए गए [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
