---
title: "SignResult"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "नए बनाए गए हस्ताक्षरों के साथ दस्तावेज़ के साइनिंग प्रक्रिया का परिणाम।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

नए बनाए गए हस्ताक्षरों के साथ दस्तावेज़ के साइनिंग प्रक्रिया का परिणाम।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | प्रक्रिया के निष्पादन समय को मिलीसेकंड में लौटाता है |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | कुल प्रोसेस किए गए हस्ताक्षर लौटाता है |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | स्रोत दस्तावेज़ का आकार लौटाता है |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | गंतव्य दस्तावेज़ का आकार लौटाता है |
|
|  | [getSucceeded()](#getSucceeded--) | नए बनाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | हस्ताक्षरों की सूची जो बनाने में विफल रहे। |
|
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


नए बनाए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


हस्ताक्षरों की सूची जो बनाने में विफल रहे।


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
