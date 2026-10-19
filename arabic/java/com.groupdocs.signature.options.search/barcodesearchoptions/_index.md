---
title: "BarcodeSearchOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات البحث التجريدية لتوقيعات الباركود."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

يمثل خيارات البحث التجريدية لتوقيعات الباركود.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | يُنشئ مثيلاً جديدًا من الفئة SearchBarcodeOptions بالقيم الافتراضية. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | يُنشئ مثيلاً جديدًا من الفئة SearchBarcodeOptions بقيمة نوع الترميز. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | يقوم بإنشاء نسخة جديدة من الفئة SearchBarcodeOptions مع نوع الترميز وقيم النص. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | يحدد خاصية Encode Type للبحث عن الباركود. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | يحدد خاصية Encode Type للبحث عن الباركود. |
|
|  | [getText()](#getText--) | يحدد نص توقيع الباركود إذا كان يجب البحث عنه ومطابقته. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يحدد نص توقيع الباركود إذا كان يجب البحث عنه ومطابقته. |
|
|  | [getMatchType()](#getMatchType--) | يحصل أو يضبط نوع مطابقة نص الباركود للبحث. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | يحصل أو يضبط نوع مطابقة نص الباركود للبحث. |
|
|  | [getReturnContent()](#getReturnContent--) | يحصل أو يضبط العلامة لالتقاط محتوى صورة الباركود للتوقيع على صفحة المستند. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | يحصل أو يضبط العلامة لالتقاط محتوى صورة الباركود للتوقيع على صفحة المستند. |
|
|  | [getReturnContentType()](#getReturnContentType--) | يحدد نوع الملف لمحتوى الصورة المعاد لتوقيع الباركود عندما تكون خاصية ReturnContent مفعلة. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | يحدد نوع الملف لمحتوى الصورة المعاد لتوقيع الباركود عندما تكون خاصية ReturnContent مفعلة. |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


يُنشئ مثيلاً جديدًا من الفئة SearchBarcodeOptions بالقيم الافتراضية.


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


يُنشئ مثيلاً جديدًا من الفئة SearchBarcodeOptions بقيمة نوع الترميز.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | يحدد نوع ترميز الباركود. |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


يقوم بإنشاء نسخة جديدة من الفئة SearchBarcodeOptions مع نوع الترميز وقيم النص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | يحدد نوع ترميز الباركود. |
|
|  | نص | java.lang.String | تعيين نص توقيع الباركود. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


يحدد خاصية Encode Type للبحث عن الباركود.
إذا لم يتم تعيين هذه القيمة، يتم تنفيذ البحث لجميع أنواع الباركود المدعومة.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


يحدد خاصية Encode Type للبحث عن الباركود.
إذا لم يتم تعيين هذه القيمة، يتم تنفيذ البحث لجميع أنواع الباركود المدعومة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


يحدد نص توقيع الباركود إذا كان يجب البحث عنه ومطابقته.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحدد نص توقيع الباركود إذا كان يجب البحث عنه ومطابقته.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


يحصل أو يضبط بحث نوع مطابقة نص الباركود. يُستخدم فقط عندما تكون خاصية Text مُعيَّنة.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


يحصل أو يضبط بحث نوع مطابقة نص الباركود. يُستخدم فقط عندما تكون خاصية Text مُعيَّنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


يحصل أو يضبط العلامة لالتقاط محتوى صورة الباركود للتوقيع على صفحة المستند.
إذا تم تعيين هذه العلامة إلى true، سيحتفظ محتوى صورة توقيع الباركود ببيانات الصورة الخام بالتنسيق المطلوب.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
بشكل افتراضي، هذا الخيار معطل.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


يحصل أو يضبط العلامة لالتقاط محتوى صورة الباركود للتوقيع على صفحة المستند.
إذا تم تعيين هذه العلامة إلى true، سيحتفظ محتوى صورة توقيع الباركود ببيانات الصورة الخام بالتنسيق المطلوب.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
بشكل افتراضي، هذا الخيار معطل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


يحدد نوع الملف لمحتوى الصورة المعاد لتوقيع الباركود عندما تكون خاصية ReturnContent مفعلة.
بشكل افتراضي يتم تعيينه إلى Null. هذا يعني إرجاع محتوى صورة الباركود بالتنسيق الأصلي.
تم تحديد تنسيق الصورة هذا في
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
القيم المدعومة المحتملة هي: FileType.JPEG، FileType.PNG، FileType.BMP.
إذا كان التنسيق المقدم غير مدعوم، سيتم إرجاع محتوى صورة الباركود بتنسيق .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


يحدد نوع الملف لمحتوى الصورة المعاد لتوقيع الباركود عندما تكون خاصية ReturnContent مفعلة.
بشكل افتراضي يتم تعيينه إلى Null. هذا يعني إرجاع محتوى صورة الباركود بالتنسيق الأصلي.
تم تحديد تنسيق الصورة هذا في
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
القيم المدعومة المحتملة هي: FileType.JPEG، FileType.PNG، FileType.BMP.
إذا كان التنسيق المقدم غير مدعوم، سيتم إرجاع محتوى صورة الباركود بتنسيق .png.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

