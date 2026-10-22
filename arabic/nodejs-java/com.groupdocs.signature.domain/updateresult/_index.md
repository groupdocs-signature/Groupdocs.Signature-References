---
title: "UpdateResult"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "نتيجة تعديل التوقيعات في المستند."
type: docs
weight: 19
url: /ar/nodejs-java/com.groupdocs.signature.domain/updateresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class UpdateResult implements IResult
```

نتيجة تعديل التوقيعات في المستند.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | يُرجِع زمن تنفيذ العملية بالميليثانية |
| [getTotalSignatures()](#getTotalSignatures--) | يُرجِع إجمالي التواقيع المعالجة |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | يرجع حجم المستند المصدر |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | يرجع حجم المستند الوجهة |
| [getSucceeded()](#getSucceeded--) | قائمة التوقيعات التي تم تعديلها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | قائمة التوقيعات التي لم يتم تحديثها [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


يُرجِع زمن تنفيذ العملية بالميليثانية

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


يرجع حجم المستند المصدر

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


يرجع حجم المستند الوجهة

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


قائمة التوقيعات التي تم تعديلها بنجاح [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


قائمة التوقيعات التي لم يتم تحديثها [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
