---
title: "ImageSearchOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات البحث لتوقيعات الصورة."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

يمثل خيارات البحث لتوقيعات الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageSearchOptions()](#ImageSearchOptions--) | يقوم بتهيئة نسخة جديدة من فئة ImageSearchOptions بالقيم الافتراضية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getReturnContent()](#getReturnContent--) | يحصل أو يضبط العلامة لالتقاط محتوى صورة التوقيع على صفحة المستند. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | يحصل أو يضبط العلامة لالتقاط محتوى صورة التوقيع على صفحة المستند. |
| [getMinContentSize()](#getMinContentSize--) | للقيمة غير الصفرية، تحدد هذه العلامة الحد الأدنى لحجم الصور لمعايير البحث. |
| [setMinContentSize(long value)](#setMinContentSize-long-) | للقيمة غير الصفرية، تحدد هذه العلامة الحد الأدنى لحجم الصور لمعايير البحث. |
| [getMaxContentSize()](#getMaxContentSize--) | للقيمة غير الصفرية، تحدد هذه العلامة الحد الأقصى لحجم الصور لمعايير البحث. |
| [setMaxContentSize(long value)](#setMaxContentSize-long-) | للقيمة غير الصفرية، تحدد هذه العلامة الحد الأقصى لحجم الصور لمعايير البحث. |
| [getReturnContentType()](#getReturnContentType--) | يحدد نوع الملف للمحتوى المعاد لتوقيع الصورة عندما تكون خاصية ReturnContent مفعلة. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | يحدد نوع الملف للمحتوى المعاد لتوقيع الصورة عندما تكون خاصية ReturnContent مفعلة. |
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


يقوم بتهيئة نسخة جديدة من فئة ImageSearchOptions بالقيم الافتراضية.

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


يحصل أو يضبط العلامة لالتقاط محتوى صورة التوقيع على صفحة المستند. إذا تم تعيين هذه العلامة إلى true، سيحتفظ محتوى توقيع الصورة ببيانات الصورة الخام بالتنسيق المطلوب ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). بشكل افتراضي هذا الخيار معطل.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


يحصل أو يضبط العلامة لالتقاط محتوى صورة التوقيع على صفحة المستند. إذا تم تعيين هذه العلامة إلى true، سيحتفظ محتوى توقيع الصورة ببيانات الصورة الخام بالتنسيق المطلوب ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). بشكل افتراضي هذا الخيار معطل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


للقيمة غير الصفرية، تحدد هذه العلامة الحد الأدنى لحجم الصور لمعايير البحث. بشكل افتراضي يتم تعيين هذه العلامة إلى صفر ولا تؤثر على نتيجة البحث.

**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


للقيمة غير الصفرية، تحدد هذه العلامة الحد الأدنى لحجم الصور لمعايير البحث. بشكل افتراضي يتم تعيين هذه العلامة إلى صفر ولا تؤثر على نتيجة البحث.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


للقيمة غير الصفرية، تحدد هذه العلامة الحد الأقصى لحجم الصور لمعايير البحث. بشكل افتراضي يتم تعيين هذه العلامة إلى صفر ولا تؤثر على نتيجة البحث.

**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


للقيمة غير الصفرية، تحدد هذه العلامة الحد الأقصى لحجم الصور لمعايير البحث. بشكل افتراضي يتم تعيين هذه العلامة إلى صفر ولا تؤثر على نتيجة البحث.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


يحدد نوع الملف للمحتوى المعاد لتوقيع الصورة عندما تكون خاصية ReturnContent مفعلة. بشكل افتراضي يتم تعيينه إلى Null. وهذا يعني إرجاع محتوى الصورة بالتنسيق الأصلي. يتم تحديد هذا التنسيق للصورة في ImageSignature.Format. القيم المدعومة الممكنة هي: FileType.JPEG، FileType.PNG، FileType.BMP. إذا كان التنسيق المقدم غير مدعوم، سيتم إرجاع محتوى الصورة بالتنسيق الأصلي.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


يحدد نوع الملف للمحتوى المعاد لتوقيع الصورة عندما تكون خاصية ReturnContent مفعلة. بشكل افتراضي يتم تعيينه إلى Null. وهذا يعني إرجاع محتوى الصورة بالتنسيق الأصلي. يتم تحديد هذا التنسيق للصورة في ImageSignature.Format. القيم المدعومة الممكنة هي: FileType.JPEG، FileType.PNG، FileType.BMP. إذا كان التنسيق المقدم غير مدعوم، سيتم إرجاع محتوى الصورة بالتنسيق الأصلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

