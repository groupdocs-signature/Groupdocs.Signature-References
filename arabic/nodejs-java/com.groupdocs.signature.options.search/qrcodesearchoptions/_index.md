---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات البحث المجردة لتوقيعات رمز الاستجابة السريعة."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

يمثل خيارات البحث المجردة لتوقيعات رمز الاستجابة السريعة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [QrCodeSearchOptions()](#QrCodeSearchOptions--) | ينشئ مثيلاً جديداً من الفئة QRCodeSearchOptions بالقيم الافتراضية. |
| [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | ينشئ مثيلاً جديداً من الفئة QRCodeSearchOptions بقيمة نوع الترميز. |
| [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة QRCodeSearchOptions بقيم نوع الترميز والنص. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | يحدد خاصية نوع الترميز للبحث عن رموز QR. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | يحدد خاصية نوع الترميز للبحث عن رموز QR. |
| [getText()](#getText--) | يحدد نص توقيع QR-Code إذا كان يجب البحث عنه ومطابقته. |
| [setText(String value)](#setText-java.lang.String-) | يحدد نص توقيع QR-Code إذا كان يجب البحث عنه ومطابقته. |
| [getMatchType()](#getMatchType--) | يحصل أو يعيّن نوع مطابقة نص QR-Code للبحث. |
| [setMatchType(int value)](#setMatchType-int-) | يحصل أو يعيّن نوع مطابقة نص QR-Code للبحث. |
| [getDataEncryption()](#getDataEncryption--) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص أو بيانات توقيع QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص أو بيانات توقيع QR-Code. |
| [getReturnContent()](#getReturnContent--) | يحصل أو يعيّن العلامة لالتقاط محتوى صورة QR-Code للتوقيع على صفحة المستند. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | يحصل أو يعيّن العلامة لالتقاط محتوى صورة QR-Code للتوقيع على صفحة المستند. |
| [getReturnContentType()](#getReturnContentType--) | يحدد نوع ملف محتوى الصورة المعادة لتوقيع QR-Code عندما تكون خاصية ReturnContent مفعلة. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | يحدد نوع ملف محتوى الصورة المعادة لتوقيع QR-Code عندما تكون خاصية ReturnContent مفعلة. |
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


ينشئ مثيلاً جديداً من الفئة QRCodeSearchOptions بالقيم الافتراضية.

### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


ينشئ مثيلاً جديداً من الفئة QRCodeSearchOptions بقيمة نوع الترميز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | يحدد نوع ترميز QR-Code. |

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


ينشئ مثيلاً جديداً من الفئة QRCodeSearchOptions بقيم نوع الترميز والنص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | يحدد نوع ترميز QR-Code. |
| نص | java.lang.String | تعيين نص توقيع QR-Code. |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


يحدد خاصية نوع الترميز للبحث عن QR-Codes. إذا لم يتم تعيين هذه القيمة، يتم تنفيذ البحث لجميع أنواع QR-Code المدعومة.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


يحدد خاصية نوع الترميز للبحث عن QR-Codes. إذا لم يتم تعيين هذه القيمة، يتم تنفيذ البحث لجميع أنواع QR-Code المدعومة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


يحدد نص توقيع QR-Code إذا كان يجب البحث عنه ومطابقته.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحدد نص توقيع QR-Code إذا كان يجب البحث عنه ومطابقته.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


يحصل أو يعيّن نوع مطابقة نص QR-Code للبحث. يُستخدم فقط عندما يتم تعيين خاصية Text.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


يحصل أو يعيّن نوع مطابقة نص QR-Code للبحث. يُستخدم فقط عندما يتم تعيين خاصية Text.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص أو بيانات توقيع QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص أو بيانات توقيع QR-Code.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


يحصل أو يعيّن العلامة لالتقاط محتوى صورة QR-Code للتوقيع على صفحة المستند. إذا تم تعيين هذه العلامة إلى true، سيحتفظ محتوى صورة توقيع QR-Code ببيانات الصورة الخام بالتنسيق المطلوب ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). بشكل افتراضي، هذا الخيار معطل.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


يحصل أو يعيّن العلامة لالتقاط محتوى صورة QR-Code للتوقيع على صفحة المستند. إذا تم تعيين هذه العلامة إلى true، سيحتفظ محتوى صورة توقيع QR-Code ببيانات الصورة الخام بالتنسيق المطلوب ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). بشكل افتراضي، هذا الخيار معطل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


يحدد نوع الملف لمحتوى الصورة المعاد لتوقيع QR-Code عندما تكون خاصية ReturnContent مفعلة. بشكل افتراضي يتم تعيينه إلى Null. هذا يعني إرجاع محتوى صورة QR-Code بالتنسيق الأصلي. يتم تحديد هذا التنسيق الصوري في QrCodeSignature.Format (). القيم المدعومة الممكنة هي: FileType.JPEG, FileType.PNG, FileType.BMP. إذا كان التنسيق المقدم غير مدعوم، سيتم إرجاع محتوى صورة QR-Code بصيغة .png الأصلية.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


يحدد نوع الملف لمحتوى الصورة المعاد لتوقيع QR-Code عندما تكون خاصية ReturnContent مفعلة. بشكل افتراضي يتم تعيينه إلى Null. هذا يعني إرجاع محتوى صورة QR-Code بالتنسيق الأصلي. يتم تحديد هذا التنسيق الصوري في QrCodeSignature.Format (). القيم المدعومة الممكنة هي: FileType.JPEG, FileType.PNG, FileType.BMP. إذا كان التنسيق المقدم غير مدعوم، سيتم إرجاع محتوى صورة QR-Code بصيغة .png الأصلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

