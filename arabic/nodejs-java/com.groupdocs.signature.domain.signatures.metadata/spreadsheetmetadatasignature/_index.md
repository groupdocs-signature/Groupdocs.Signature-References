---
title: "SpreadsheetMetadataSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع بيانات الجدول الإلكتروني الوصفية."
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/spreadsheetmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class SpreadsheetMetadataSignature extends MetadataSignature
```

يحتوي على خصائص توقيع بيانات الجدول الإلكتروني الوصفية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SpreadsheetMetadataSignature(String name)](#SpreadsheetMetadataSignature-java.lang.String-) | ينشئ Spreadsheet Metadata Signature بالاسم المحدد مسبقًا والقيمة الفارغة. |
| [SpreadsheetMetadataSignature(String name, Object value)](#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-) | ينشئ توقيع بيانات تعريف جدول البيانات مع قيم محددة مسبقًا. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | استنساخ كائن توقيع Metadata. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ نسخة من توقيع بيانات تعريف جدول البيانات بالقيمة المعطاة. |
| [toString()](#toString--) | يحول إلى سلسلة باستخدام طريقة ToString() المتجاوزة |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | يحول إلى سلسلة بالتنسيق المحدد |
### SpreadsheetMetadataSignature(String name) {#SpreadsheetMetadataSignature-java.lang.String-}
```
public SpreadsheetMetadataSignature(String name)
```


ينشئ Spreadsheet Metadata Signature بالاسم المحدد مسبقًا والقيمة الفارغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم توقيع بيانات تعريف جدول البيانات. |

### SpreadsheetMetadataSignature(String name, Object value) {#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-}
```
public SpreadsheetMetadataSignature(String name, Object value)
```


ينشئ توقيع بيانات تعريف جدول البيانات مع قيم محددة مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن توقيع Metadata. |
| قيمة | java.lang.Object | قيمة توقيع Metadata. |

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


استنساخ نسخة من توقيع بيانات تعريف جدول البيانات بالقيمة المعطاة.

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
