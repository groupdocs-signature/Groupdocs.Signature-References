---
title: "SearchResult"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "نتيجة البحث عن التوقيعات في المستند المحدد."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

نتيجة البحث عن التوقيعات في المستند المحدد.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | يعيد وقت تنفيذ عملية البحث بالمللي ثانية. |
| [getTotalSignatures()](#getTotalSignatures--) | يعيد إجمالي التوقيعات التي تمت معالجتها بواسطة عملية البحث |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | يرجع حجم المستند المصدر |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | يعيد حجم المستند الهدف. |
| [getSucceeded()](#getSucceeded--) | قائمة التوقيعات التي تم العثور عليها [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | قائمة التوقيعات [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) التي فشلت في عملية البحث وفقًا لمعايير البحث. |
| [getSignatures()](#getSignatures--) | قائمة التوقيعات المكتشفة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | يوفر تحويلًا إلى قائمة من التوقيعات ذات النوع القوي. |
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


يعيد وقت تنفيذ عملية البحث بالمللي ثانية.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


يعيد إجمالي التوقيعات التي تمت معالجتها بواسطة عملية البحث

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


يعيد حجم المستند الهدف. بالنسبة لطريقة Search دائمًا ما يعيد 0.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


قائمة التوقيعات التي تم العثور عليها [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). ستكون هذه القائمة دائمًا مساوية لخاصية Signatures (\#getSignatures.getSignatures/\#setSignatures(List).setSignatures(List)).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


قائمة التوقيعات [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) التي فشلت في عملية البحث وفقًا لمعايير البحث. غير مدعوم في الإصدار الحالي.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


قائمة التوقيعات المكتشفة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


يوفر تحويلًا إلى قائمة من التوقيعات ذات النوع القوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - يعيد قائمة بنوع التوقيع المحدد.

T : نوع التوقيعات في القائمة.
### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

