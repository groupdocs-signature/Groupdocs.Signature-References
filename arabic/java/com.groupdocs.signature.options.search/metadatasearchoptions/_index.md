---
title: "MetadataSearchOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات البحث المجردة لتواقيع البيانات الوصفية."
type: docs
weight: 15
url: /ar/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

يمثل خيارات البحث المجردة لتواقيع البيانات الوصفية.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | يُنشئ مثيلاً جديدًا من الفئة SearchMetadataOptions بالقيم الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يحدد اسم توقيع البيانات الوصفية إذا كان يجب البحث عنه ومطابقته. |
|
|  | [setName(String value)](#setName-java.lang.String-) | يحدد اسم توقيع البيانات الوصفية إذا كان يجب البحث عنه ومطابقته. |
|
|  | [getNameMatchType()](#getNameMatchType--) | يحصل أو يضبط نوع مطابقة اسم البيانات الوصفية للبحث. |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | يحصل أو يضبط نوع مطابقة اسم البيانات الوصفية للبحث. |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | يشير إلى ما إذا كان يجب تضمين خصائص المستند المدمجة مثل إحصاءات المستند، المعلومات وغيرها في نتيجة البحث. |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | يشير إلى ما إذا كان يجب تضمين خصائص المستند المدمجة مثل إحصاءات المستند، المعلومات وغيرها في نتيجة البحث. |
|
|  | [getDataEncryption()](#getDataEncryption--) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات. |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


يُنشئ مثيلاً جديدًا من الفئة SearchMetadataOptions بالقيم الافتراضية.


### getName() {#getName--}
```
public final String getName()
```


يحدد اسم توقيع البيانات الوصفية إذا كان يجب البحث عنه ومطابقته.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحدد اسم توقيع البيانات الوصفية إذا كان يجب البحث عنه ومطابقته.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


يحصل أو يضبط نوع مطابقة اسم البيانات الوصفية للبحث. يُستخدم فقط عندما يتم تعيين خاصية Name.


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


يحصل أو يضبط نوع مطابقة اسم البيانات الوصفية للبحث. يُستخدم فقط عندما يتم تعيين خاصية Name.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


يشير إلى ما إذا كان يجب تضمين خصائص المستند المدمجة مثل إحصاءات المستند، المعلومات وغيرها في نتيجة البحث.
هذه العلامة ذات معنى لأنواع ملفات العروض التقديمية، وجداول البيانات، ومعالجة النصوص.


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


يشير إلى ما إذا كان يجب تضمين خصائص المستند المدمجة مثل إحصاءات المستند، المعلومات وغيرها في نتيجة البحث.
هذه العلامة ذات معنى لأنواع ملفات العروض التقديمية، وجداول البيانات، ومعالجة النصوص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

