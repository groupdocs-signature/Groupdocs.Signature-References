---
title: "UpdateResult"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "نتيجة تعديل التواقيع في المستند."
type: docs
weight: 19
url: /ar/java/com.groupdocs.signature.domain/updateresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class UpdateResult implements IResult
```

نتيجة تعديل التواقيع في المستند.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | يُرجِع وقت تنفيذ العملية بالمللي ثانية |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | يُرجِع إجمالي التواقيع المعالجة |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | يُرجِع حجم المستند المصدر |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | يُرجِع حجم المستند الهدف |
|
|  | [getSucceeded()](#getSucceeded--) | قائمة التواقيع التي تم تعديلها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | قائمة التواقيع التي لم يتم تحديثها [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


يُرجِع وقت تنفيذ العملية بالمللي ثانية


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


يُرجِع حجم المستند المصدر


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


يُرجِع حجم المستند الهدف


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


قائمة التواقيع التي تم تعديلها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


قائمة التواقيع التي لم يتم تحديثها [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
