---
title: "DeleteResult"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "نتيجة حذف التوقيعات من المستند."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

نتيجة حذف التواقيع من المستند.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | يرجع وقت تنفيذ العملية بالمللي ثانية. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | يعيد إجمالي التوقيعات المعالجة. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | يعيد حجم المستند الأصلي. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | يعيد حجم المستند المحدث. |
|
|  | [getSucceeded()](#getSucceeded--) | قائمة التوقيعات التي تم حذفها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | قائمة التوقيعات التي لم يتم حذفها [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
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


يعيد إجمالي التوقيعات المعالجة.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


يعيد حجم المستند الأصلي.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


يعيد حجم المستند المحدث.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


قائمة التوقيعات التي تم حذفها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


قائمة التوقيعات التي لم يتم حذفها [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
