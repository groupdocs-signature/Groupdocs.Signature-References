---
title: "SpreadsheetMetadataSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع بيانات تعريف جدول البيانات."
type: docs
weight: 17
url: /ar/java/com.groupdocs.signature.domain.signatures.metadata/spreadsheetmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class SpreadsheetMetadataSignature extends MetadataSignature
```

يحتوي على خصائص توقيع بيانات تعريف جدول البيانات.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetMetadataSignature(String name)](#SpreadsheetMetadataSignature-java.lang.String-) | ينشئ Spreadsheet Metadata Signature باسم محدد مسبقًا وقيمة فارغة. |
|
|  | [SpreadsheetMetadataSignature(String name, Object value)](#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-) | ينشئ Spreadsheet Metadata Signature بقيم محددة مسبقًا. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [deepClone()](#deepClone--) | استنساخ كائن توقيع البيانات الوصفية. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ كائن Spreadsheet Metadata Signature بالقيمة المعطاة. |
|
|  | [toString()](#toString--) | يحوِّل إلى String باستخدام طريقة ToString() المتجاوزة |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | يحوِّل إلى String باستخدام التنسيق المحدد |
|
### SpreadsheetMetadataSignature(String name) {#SpreadsheetMetadataSignature-java.lang.String-}
```
public SpreadsheetMetadataSignature(String name)
```


ينشئ Spreadsheet Metadata Signature باسم محدد مسبقًا وقيمة فارغة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم Spreadsheet Metadata Signature. |
|

### SpreadsheetMetadataSignature(String name, Object value) {#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-}
```
public SpreadsheetMetadataSignature(String name, Object value)
```


ينشئ Spreadsheet Metadata Signature بقيم محددة مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن توقيع البيانات الوصفية. |
|
|  | قيمة | java.lang.Object | قيمة توقيع البيانات الوصفية. |
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


استنساخ كائن Spreadsheet Metadata Signature بالقيمة المعطاة.


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

