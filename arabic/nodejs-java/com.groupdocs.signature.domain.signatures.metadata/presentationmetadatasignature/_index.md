---
title: "PresentationMetadataSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع بيانات العرض التقديمي الوصفية."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

يحتوي على خصائص توقيع بيانات العرض التقديمي الوصفية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | ينشئ Presentation Metadata Signature مع اسم محدد مسبقًا وقيمة فارغة |
| [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | ينشئ Presentation Metadata Signature مع قيم محددة مسبقًا |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | استنساخ كائن توقيع Metadata. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ نسخة من Slides Metadata Signature مع القيمة المعطاة. |
| [toString()](#toString--) | يحول إلى سلسلة باستخدام طريقة ToString() المتجاوزة |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | يحول إلى سلسلة بالتنسيق المحدد |
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


ينشئ Presentation Metadata Signature مع اسم محدد مسبقًا وقيمة فارغة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم توقيع البيانات الوصفية للعرض |

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


ينشئ Presentation Metadata Signature مع قيم محددة مسبقًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن توقيع البيانات الوصفية |
| قيمة | java.lang.Object | قيمة توقيع البيانات الوصفية |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


استنساخ كائن توقيع Metadata.

**Returns:**
java.lang.Object - يعيد نسخة مستنسخة من كائن توقيع Metadata
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


استنساخ نسخة من Slides Metadata Signature مع القيمة المعطاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object | قيمة للكائن المستنسخ الجديد. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toString() {#toString--}
```
public String toString()
```


يحول إلى سلسلة باستخدام طريقة ToString() المتجاوزة

**Returns:**
java.lang.String - يُعيد قيمة توقيع البيانات الوصفية كـ String.

--------------------

يحوّل خاصية منطقية إلى "True" أو "False". بالنسبة لنوع بيانات آخر سيتم استخدام مزود تنسيق البيانات الافتراضي.
### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


يحول إلى سلسلة بالتنسيق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التنسيق | java.lang.String | سلسلة تنسيق البيانات. |
|  | المزود | com.aspose.ms.System.IFormatProvider | مزود تنسيق البيانات لاستخدامه مع عمليات تحويل البيانات. |

--------------------

يحوّل خاصية منطقية إلى "True" أو "False". |

**Returns:**
java.lang.String - يُعيد قيمة توقيع البيانات الوصفية كـ String.
