---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "مجموعة من كائنات توقيع البيانات الوصفية."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

مجموعة من كائنات توقيع البيانات الوصفية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MetadataSignatureCollection()](#MetadataSignatureCollection--) | ينشئ مجموعة من توقيع البيانات الوصفية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يحصل على عدد العناصر في المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(String name)](#contains-java.lang.String-) | يرجع true إذا كان Metadata بالاسم المحدد موجودًا في المجموعة. |
| [indexOf(String name)](#indexOf-java.lang.String-) | يحصل على فهرس الخاصية بالاسم. |
| [remove(String name)](#remove-java.lang.String-) | يزيل Metadata Signature بالاسم المحدد من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل Metadata Signature في الفهرس المحدد. |
| [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | أضف كائن Metadata Signature إلى المجموعة. |
| [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | أضف مجموعة Metadata Signature. |
| [deepClone()](#deepClone--) | استنسخ فئة مجموعة Metadata Signature مع عناصر Metadata Signature. |
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


ينشئ مجموعة من توقيع البيانات الوصفية.

### getCount() {#getCount--}
```
public final int getCount()
```


يحصل على عدد العناصر في المجموعة.

**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


يزيل جميع العناصر من المجموعة.

### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


يرجع true إذا كان Metadata بالاسم المحدد موجودًا في المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم غير حساس لحالة الأحرف للخاصية. |

**Returns:**
boolean - True إذا كان Metadata موجودًا في المجموعة؛ false خلاف ذلك.
### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


يحصل على فهرس الخاصية بالاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم غير حساس لحالة الأحرف لـ MetadataSignature. |

**Returns:**
int - الفهرس القائم على الصفر. قيمة سلبية إذا لم يُعثر عليه.
### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


يزيل Metadata Signature بالاسم المحدد من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم غير حساس لحالة الأحرف لـ Metadata Signature. |

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


يزيل Metadata Signature في الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int | الفهرس القائم على الصفر. |

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


أضف كائن Metadata Signature إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | توقيع Metadata ليُضاف إلى المجموعة. |

--------------------

يرمي استثناءً إذا لم تكن قيمة الاسم فريدة في المجموعة الحالية بالكامل |

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


أضف مجموعة Metadata Signature.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | مجموعة من التوقيعات للإضافة. |

--------------------

يرمي استثناءً إذا لم تكن قيمة الاسم فريدة في المجموعة الحالية بالكامل |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


استنسخ فئة مجموعة Metadata Signature مع عناصر Metadata Signature.

**Returns:**
java.lang.Object - يرجع نسخة منسوخة مع عناصر Signature Items المستنسخة
