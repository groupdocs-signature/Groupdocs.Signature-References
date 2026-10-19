---
title: "DocumentResultSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "نتيجة معالجة عملية توقيع مستند الأرشيف للمستند مع التوقيعات التي تم إنشاؤها حديثًا."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

نتيجة معالجة عملية توقيع مستند الأرشيف للمستند مع التوقيعات التي تم إنشاؤها حديثًا.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFileName()](#getFileName--) | اسم ملف المستند |
|
|  | [getProcessingTime()](#getProcessingTime--) | يُرجِع وقت تنفيذ العملية بالمللي ثانية |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | يُرجِع إجمالي التواقيع المعالجة |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | يُرجِع حجم المستند المصدر |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | يُرجِع حجم المستند الهدف |
|
|  | [getSucceeded()](#getSucceeded--) | قائمة التواقيع التي تم معالجتها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | قائمة التواقيع التي فشلت أثناء العملية [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | إذا تم معالجة المستند بخطأ، ستحتوي هذه الخاصية على رسالة الخطأ |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


اسم ملف المستند


**Returns:**
java.lang.String
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


قائمة التواقيع التي تم معالجتها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


قائمة التواقيع التي فشلت أثناء العملية [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


إذا تم معالجة المستند بخطأ، ستحتوي هذه الخاصية على رسالة الخطأ


**Returns:**
java.lang.String
