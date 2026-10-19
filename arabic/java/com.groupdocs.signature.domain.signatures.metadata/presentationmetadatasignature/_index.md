---
title: "PresentationMetadataSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع بيانات تعريف العرض التقديمي."
type: docs
weight: 16
url: /ar/java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

يحتوي على خصائص توقيع بيانات تعريف العرض التقديمي.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | إنشاء توقيع بيانات تعريف العرض التقديمي مع اسم محدد مسبقًا وقيمة فارغة |
|
|  | [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | إنشاء توقيع بيانات تعريف العرض التقديمي مع قيم محددة مسبقًا |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [deepClone()](#deepClone--) | استنساخ كائن توقيع البيانات الوصفية. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ نسخة من توقيع بيانات تعريف الشرائح مع القيمة المعطاة. |
|
|  | [toString()](#toString--) | يحوِّل إلى String باستخدام طريقة ToString() المتجاوزة |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | يحوِّل إلى String باستخدام التنسيق المحدد |
|
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


إنشاء توقيع بيانات تعريف العرض التقديمي مع اسم محدد مسبقًا وقيمة فارغة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم توقيع بيانات تعريف العرض التقديمي |
|

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


إنشاء توقيع بيانات تعريف العرض التقديمي مع قيم محددة مسبقًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن توقيع البيانات الوصفية |
|
|  | قيمة | java.lang.Object | قيمة توقيع البيانات الوصفية |
|

### deepClone() {#deepClone--}
```
public Object deepClone()
```


استنساخ كائن توقيع البيانات الوصفية.


**Returns:**
java.lang.Object - يُرجِع نسخة مستنسخة من Metadata Signature

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


استنساخ نسخة من توقيع بيانات تعريف الشرائح مع القيمة المعطاة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | java.lang.Object | القيمة للكائن المستنسخ الجديد. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toString() {#toString--}
```
public String toString()
```


يحوِّل إلى String باستخدام طريقة ToString() المتجاوزة


**Returns:**
java.lang.String - يُعيد قيمة توقيع Metadata كـ String.

<br />

*** ** * ** ***

يحوِّل خاصية منطقية إلى "True" أو "False". لنوع بيانات آخر سيتم استخدام مزود تنسيق البيانات الافتراضي.

<br />


### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


يحوِّل إلى String باستخدام التنسيق المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تنسيق | java.lang.String | سلسلة تنسيق البيانات. |
|
|  | مزود | com.aspose.ms.System.IFormatProvider | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

<br />

*** ** * ** ***

يحوِّل خاصية منطقية إلى "True" أو "False".

<br />

|

**Returns:**
java.lang.String - يُعيد قيمة توقيع Metadata كـ String.

