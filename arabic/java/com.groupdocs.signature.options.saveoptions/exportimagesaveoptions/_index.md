---
title: "ExportImageSaveOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "خيارات الحفظ لتصدير المستندات إلى صورة."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

خيارات الحفظ لتصدير المستندات إلى صورة.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | ينشئ مثيلاً جديدًا لفئة ExportAsImageSaveOptions بالقيم الافتراضية. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | ينشئ مثيلاً جديدًا لفئة ExportAsImageSaveOptions بالتنسيق المحدد للملف. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | يحصل أو يضبط رقم صفحة المستند للتصدير. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | يحصل أو يضبط رقم صفحة المستند للتصدير. |
|
|  | [getExportAllPages()](#getExportAllPages--) | علم لتصدير كل صفحة. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | علم لتصدير كل صفحة. |
|
|  | [getPagesSetup()](#getPagesSetup--) | خيارات لتحديد الصفحات التي سيتم توقيعها. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | خيارات لتحديد الصفحات التي سيتم توقيعها. |
|
|  | [getPageColumns()](#getPageColumns--) | يحصل أو يضبط عدد الأعمدة للصور المُصدَّرة. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | يحصل أو يضبط عدد الأعمدة للصور المُصدَّرة. |
|
|  | [getBorder()](#getBorder--) | يحصل أو يضبط إعدادات حدود الصورة. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | يحصل أو يضبط إعدادات حدود الصورة. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | ضع صفحات المستند في إطارات مختلفة في صورة Tiff. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | ضع صفحات المستند في إطارات مختلفة في صورة Tiff. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


ينشئ مثيلاً جديدًا لفئة ExportAsImageSaveOptions بالقيم الافتراضية.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


ينشئ مثيلاً جديدًا لفئة ExportAsImageSaveOptions بالتنسيق المحدد للملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | int | تنسيق ملف صورة الإخراج. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


يحصل أو يضبط رقم صفحة المستند للتصدير.
القيمة الدنيا هي 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


يحصل أو يضبط رقم صفحة المستند للتصدير.
القيمة الدنيا هي 1.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


علم لتصدير كل صفحة.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


علم لتصدير كل صفحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


خيارات لتحديد الصفحات التي سيتم توقيعها.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


خيارات لتحديد الصفحات التي سيتم توقيعها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


يحصل أو يضبط عدد الأعمدة للصور المُصدَّرة.
استخدم هذه الخاصية إذا كنت تحتاج إلى وضع الصور في صف.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


يحصل أو يضبط عدد الأعمدة للصور المُصدَّرة.
استخدم هذه الخاصية إذا كنت تحتاج إلى وضع الصور في صف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


الحصول على أو تعيين إعدادات حدود الصورة. بشكل افتراضي لا يتم تعيين هذه القيمة.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


الحصول على أو تعيين إعدادات حدود الصورة. بشكل افتراضي لا يتم تعيين هذه القيمة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


ضع صفحات المستند في إطارات مختلفة في صورة Tiff.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


ضع صفحات المستند في إطارات مختلفة في صورة Tiff.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
