---
title: "VerificationResult"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "مثيل للاحتفاظ بنتائج عملية التحقق."
type: docs
weight: 20
url: /ar/nodejs-java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

مثيل للاحتفاظ بنتائج عملية التحقق.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | يعيد وقت تنفيذ العملية بالمللي ثانية. |
| [getTotalSignatures()](#getTotalSignatures--) | يُرجِع إجمالي التواقيع المعالجة |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | يعيد حجم المستند المصدر بالبايت |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | يعيد حجم المستند الهدف. |
| [getSucceeded()](#getSucceeded--) | قائمة التوقيعات التي تم التحقق منها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [isValid()](#isValid--) | يعيد true إذا كانت عملية التحقق ناجحة وإلا false. |
| [setValid(boolean value)](#setValid-boolean-) | يعيد true إذا كانت عملية التحقق ناجحة وإلا false. |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


يعيد وقت تنفيذ العملية بالمللي ثانية.

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


يعيد حجم المستند المصدر بالبايت

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


يعيد حجم المستند الهدف. بالنسبة للتحقق، هذا المتغير دائمًا ما يحتوي على صفر.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


قائمة التوقيعات التي تم التحقق منها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). حاليًا هذه الخاصية غير مدعومة.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


يعيد true إذا كانت عملية التحقق ناجحة وإلا false.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


يعيد true إذا كانت عملية التحقق ناجحة وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

