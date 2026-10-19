---
title: "VerificationResult"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "مثيل للاحتفاظ بنتائج عملية التحقق."
type: docs
weight: 20
url: /ar/java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

مثيل للاحتفاظ بنتائج عملية التحقق.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | يرجع وقت تنفيذ العملية بالمللي ثانية. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | يُرجِع إجمالي التواقيع المعالجة |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | يرجع حجم المستند المصدر بالبايت |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | يرجع حجم المستند الهدف. |
|
|  | [getSucceeded()](#getSucceeded--) | قائمة التواقيع التي تم التحقق منها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [isValid()](#isValid--) | يرجع true إذا كانت عملية Verification ناجحة وإلا false. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | يرجع true إذا كانت عملية Verification ناجحة وإلا false. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


يرجع وقت تنفيذ العملية بالمللي ثانية.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


يُرجِع إجمالي التواقيع المعالجة


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


يرجع حجم المستند المصدر بالبايت


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


يرجع حجم المستند الهدف. بالنسبة للتحقق، هذه المتغير دائمًا يحتوي على صفر.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


قائمة التواقيع التي تم التحقق منها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
حاليًا هذه الخاصية غير مدعومة.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


يرجع true إذا كانت عملية Verification ناجحة وإلا false.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


يرجع true إذا كانت عملية Verification ناجحة وإلا false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

