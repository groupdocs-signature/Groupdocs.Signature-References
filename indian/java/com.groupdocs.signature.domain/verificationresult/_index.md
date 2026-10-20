---
title: "VerificationResult"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "सत्यापन प्रक्रिया के परिणामों को रखने के लिए इंस्टेंस।"
type: docs
weight: 20
url: /hi/java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

सत्यापन प्रक्रिया के परिणामों को रखने के लिए इंस्टेंस।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | प्रक्रिया के निष्पादन समय को मिलीसेकंड में लौटाता है। |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | कुल प्रोसेस किए गए हस्ताक्षर लौटाता है |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | स्रोत दस्तावेज़ का आकार बाइट्स में लौटाता है |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | गंतव्य दस्तावेज़ का आकार लौटाता है। |
|
|  | [getSucceeded()](#getSucceeded--) | सफलतापूर्वक सत्यापित हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [isValid()](#isValid--) | यदि सत्यापन प्रक्रिया सफल रही तो true लौटाता है, अन्यथा false। |
|
|  | [setValid(boolean value)](#setValid-boolean-) | यदि सत्यापन प्रक्रिया सफल रही तो true लौटाता है, अन्यथा false। |
|
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


कुल प्रोसेस किए गए हस्ताक्षर लौटाता है


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


स्रोत दस्तावेज़ का आकार बाइट्स में लौटाता है


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


गंतव्य दस्तावेज़ का आकार लौटाता है। सत्यापन के लिए यह चर हमेशा शून्य रखता है।


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


सफलतापूर्वक सत्यापित हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
वर्तमान में यह प्रॉपर्टी समर्थित नहीं है।


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


यदि सत्यापन प्रक्रिया सफल रही तो true लौटाता है, अन्यथा false।


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


यदि सत्यापन प्रक्रिया सफल रही तो true लौटाता है, अन्यथा false।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

