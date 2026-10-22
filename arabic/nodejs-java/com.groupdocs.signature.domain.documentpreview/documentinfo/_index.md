---
title: "DocumentInfo"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يعرف خصائص وصف المستند."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

يعرف خصائص وصف المستند.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DocumentInfo()](#DocumentInfo--) | يقوم بتهيئة نسخة جديدة من الفئة [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPageCount()](#getPageCount--) | عدد صفحات المستند. |
| [setPageCount(int value)](#setPageCount-int-) | عدد صفحات المستند. |
| [getPages()](#getPages--) | مجموعة أوصاف صفحات المستند. |
| [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | مجموعة أوصاف صفحات المستند. |
| [getWidthForMaxHeight()](#getWidthForMaxHeight--) | يحدد العرض للحد الأقصى لارتفاع الصفحة. |
| [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | يحدد العرض للحد الأقصى لارتفاع الصفحة. |
| [getMaxPageHeight()](#getMaxPageHeight--) | يحدد الحد الأقصى لارتفاع الصفحة. |
| [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | يحدد الحد الأقصى لارتفاع الصفحة. |
| [getFileType()](#getFileType--) | نوع تنسيق الملف. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | نوع تنسيق الملف. |
| [getSize()](#getSize--) | حجم المستند بالبايت. |
| [setSize(long value)](#setSize-long-) | حجم المستند بالبايت. |
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
| [getTextSignatures()](#getTextSignatures--) | مجموعة توقيعات النص في المستند. |
| [getImageSignatures()](#getImageSignatures--) | مجموعة توقيعات الصور في المستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature). |
| [getDigitalSignatures()](#getDigitalSignatures--) | مجموعة التوقيعات الرقمية للمستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature). |
| [getBarcodeSignatures()](#getBarcodeSignatures--) | مجموعة توقيعات الباركود في المستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature). |
| [getQrCodeSignatures()](#getQrCodeSignatures--) | مجموعة توقيعات رمز الاستجابة السريعة (QR-code) في المستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature). |
| [getFormFieldSignatures()](#getFormFieldSignatures--) | مجموعة توقيعات حقول النموذج في المستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature). |
| [getFormFields()](#getFormFields--) | مجموعة جميع حقول النموذج المدعومة الموجودة في المستند. |
| [getMetadataSignatures()](#getMetadataSignatures--) | مجموعة توقيعات البيانات الوصفية للمستند. |
| [getProcessLogs()](#getProcessLogs--) | مجموعة عمليات تاريخ المستند مثل التوقيع، التحديث، الحذف. |
| [getSignatures()](#getSignatures--) | مجموعة جميع أنواع توقيعات المستند [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


يقوم بتهيئة نسخة جديدة من الفئة [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo).

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


عدد صفحات المستند.

**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


عدد صفحات المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


مجموعة أوصاف صفحات المستند.

**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


مجموعة أوصاف صفحات المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


يحدد العرض للحد الأقصى لارتفاع الصفحة.

**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


يحدد العرض للحد الأقصى لارتفاع الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


يحدد الحد الأقصى لارتفاع الصفحة.

**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


يحدد الحد الأقصى لارتفاع الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


نوع تنسيق الملف.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


نوع تنسيق الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


حجم المستند بالبايت.

**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


حجم المستند بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageWidth | int |  |
| pageHeight | int |  |
| pageIndex | int |  |

**Returns:**
[PageInfo](../../com.groupdocs.signature.domain/pageinfo)
### getTextSignatures() {#getTextSignatures--}
```
public final List<TextSignature> getTextSignatures()
```


مجموعة توقيعات النص في المستند.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


مجموعة توقيعات الصور في المستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


مجموعة التوقيعات الرقمية للمستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


مجموعة توقيعات الباركود في المستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


مجموعة توقيعات رمز الاستجابة السريعة (QR-code) في المستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


مجموعة توقيعات حقول النموذج في المستند التي تم إضافتها أو تحديثها بواسطة طرق [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


مجموعة جميع حقول النماذج المدعومة الموجودة في المستند. هذه الخاصية مدعومة فقط لأنواع مستندات PDF ومعالجة Word.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


مجموعة توقيعات البيانات الوصفية للمستند.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


مجموعة عمليات تاريخ المستند مثل التوقيع، التحديث، الحذف.

**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


مجموعة جميع أنواع توقيعات المستند [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
