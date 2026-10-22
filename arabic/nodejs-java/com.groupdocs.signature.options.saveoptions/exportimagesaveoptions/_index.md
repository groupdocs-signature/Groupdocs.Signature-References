---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "خيارات الحفظ لتصدير المستندات إلى صورة."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

خيارات الحفظ لتصدير المستندات إلى صورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ExportImageSaveOptions()](#ExportImageSaveOptions--) | ينشئ نسخة جديدة من فئة ExportAsImageSaveOptions بالقيم الافتراضية. |
| [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | ينشئ نسخة جديدة من فئة ExportAsImageSaveOptions بالتنسيق المحدد للملف. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | يحصل أو يحدد رقم صفحة المستند للتصدير. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | يحصل أو يحدد رقم صفحة المستند للتصدير. |
| [getExportAllPages()](#getExportAllPages--) | علامة لتصدير كل صفحة. |
| [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | علامة لتصدير كل صفحة. |
| [getPagesSetup()](#getPagesSetup--) | خيارات لتحديد الصفحات التي سيتم توقيعها. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | خيارات لتحديد الصفحات التي سيتم توقيعها. |
| [getPageColumns()](#getPageColumns--) | يحصل أو يحدد عدد الأعمدة للصور المصدرة. |
| [setPageColumns(int value)](#setPageColumns-int-) | يحصل أو يحدد عدد الأعمدة للصور المصدرة. |
| [getBorder()](#getBorder--) | يحصل أو يحدد إعدادات حدود الصورة. |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | يحصل أو يحدد إعدادات حدود الصورة. |
| [getTiffMultipage()](#getTiffMultipage--) | ضع صفحات المستند في إطارات مختلفة في صورة Tiff. |
| [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | ضع صفحات المستند في إطارات مختلفة في صورة Tiff. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


ينشئ نسخة جديدة من فئة ExportAsImageSaveOptions بالقيم الافتراضية.

### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


ينشئ نسخة جديدة من فئة ExportAsImageSaveOptions بالتنسيق المحدد للملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileFormat | int | تنسيق ملف الصورة الناتج. |

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


يحصل أو يحدد رقم صفحة المستند للتصدير. الحد الأدنى للقيمة هو 1.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


يحصل أو يحدد رقم صفحة المستند للتصدير. الحد الأدنى للقيمة هو 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


علامة لتصدير كل صفحة.

**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


علامة لتصدير كل صفحة.

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


يحصل أو يحدد عدد الأعمدة للصور المصدرة. استخدم هذه الخاصية إذا كنت بحاجة لوضع الصور في صف.

**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


يحصل أو يحدد عدد الأعمدة للصور المصدرة. استخدم هذه الخاصية إذا كنت بحاجة لوضع الصور في صف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


يحصل أو يحدد إعدادات حدود الصورة. بشكل افتراضي لا يتم تعيين هذه القيمة.

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


يحصل أو يحدد إعدادات حدود الصورة. بشكل افتراضي لا يتم تعيين هذه القيمة.

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
