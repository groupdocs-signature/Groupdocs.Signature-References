---
title: "QrCodeSignOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات توقيع رمز الاستجابة السريعة QR-Code."
type: docs
weight: 15
url: /ar/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

يمثل خيارات توقيع رمز الاستجابة السريعة QR-Code.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | يقوم بتهيئة نسخة جديدة من الفئة QRCodeSignOptions بالقيم الافتراضية. |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | يقوم بتهيئة نسخة جديدة من الفئة QRCodeSignOptions بالنص. |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | يُهيئ مثيلاً جديدًا من الفئة **BarcodeSignOptions** بالنص. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | يحصل أو يضبط نوع QRCode. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | يحصل أو يضبط نوع QRCode. |
|
|  | [getForeColor()](#getForeColor--) | الحصول أو تعيين لون المقدمة لأشرطة QR-Code |
استخدام هذه الخاصية قد يسبب مشاكل في التحقق.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | الحصول أو تعيين لون المقدمة لأشرطة QR-Code |
استخدام هذه الخاصية قد يسبب مشاكل في التحقق.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | الحصول أو تعيين لون المقدمة لأشرطة QR-Code |
استخدام هذه الخاصية قد يسبب مشاكل في التحقق.
|
|  | [getInnerMargins()](#getInnerMargins--) | الحصول أو تعيين المسافة بين عناصر QRCode وحدود الصورة الناتجة. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | الحصول أو تعيين المسافة بين عناصر QRCode وحدود الصورة الناتجة. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | الحصول أو تعيين محاذاة النص في صورة QR-code الناتجة. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | الحصول أو تعيين محاذاة النص في صورة QR-code الناتجة. |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | الحصول أو تعيين اسم ملف صورة شعار QR-code. |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | الحصول أو تعيين اسم ملف صورة شعار QR-code. |
|
|  | [getLogoStream()](#getLogoStream--) | الحصول أو تعيين تدفق صورة شعار QR-code. |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | الحصول أو تعيين تدفق صورة شعار QR-code. |
|
|  | [getData()](#getData--) | الحصول أو تعيين كائن مخصص لتسلسله إلى محتوى QR-Code. |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | الحصول أو تعيين كائن مخصص لتسلسله إلى محتوى QR-Code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات. |
|
|  | [getReturnContent()](#getReturnContent--) | الحصول أو تعيين العلامة للحصول على محتوى صورة QR-Code لتوقيع تم وضعه على صفحة المستند. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | الحصول أو تعيين العلامة للحصول على محتوى صورة QR-Code لتوقيع تم وضعه على صفحة المستند. |
|
|  | [getReturnContentType()](#getReturnContentType--) | تحديد نوع الملف لمحتوى الصورة المرجعة لتوقيع QR-Code عندما تكون خاصية ReturnContent مفعلة. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | تحديد نوع الملف لمحتوى الصورة المرجعة لتوقيع QR-Code عندما تكون خاصية ReturnContent مفعلة. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


يقوم بتهيئة نسخة جديدة من الفئة QRCodeSignOptions بالقيم الافتراضية.


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


يقوم بتهيئة نسخة جديدة من الفئة QRCodeSignOptions بالنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص التوقيع. |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


يُهيئ مثيلاً جديدًا من الفئة **BarcodeSignOptions** بالنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص QRCode |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | نوع ترميز QRCode انظر [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


يحصل أو يضبط نوع QRCode.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


يحصل أو يضبط نوع QRCode.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


الحصول أو تعيين لون المقدمة لأشرطة QR-Code
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


الحصول أو تعيين لون المقدمة لأشرطة QR-Code
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


الحصول أو تعيين لون المقدمة لأشرطة QR-Code
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


الحصول أو تعيين المسافة بين عناصر QRCode وحدود الصورة الناتجة.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


الحصول أو تعيين المسافة بين عناصر QRCode وحدود الصورة الناتجة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


الحصول أو تعيين محاذاة النص في صورة QR-code الناتجة.
القيمة الافتراضية هي None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


الحصول أو تعيين محاذاة النص في صورة QR-code الناتجة.
القيمة الافتراضية هي None.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


الحصول أو تعيين اسم ملف صورة شعار QR-code.
هذه الخاصية تُستخدم فقط إذا لم يتم تحديد LogoStream.
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


الحصول أو تعيين اسم ملف صورة شعار QR-code.
هذه الخاصية تُستخدم فقط إذا لم يتم تحديد LogoStream.
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


الحصول أو تعيين تدفق صورة شعار QR-code.
إذا تم تحديد هذه الخاصية فستُستخدم دائمًا بدلاً من LogoGuid.
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


الحصول أو تعيين تدفق صورة شعار QR-code.
إذا تم تحديد هذه الخاصية فستُستخدم دائمًا بدلاً من LogoGuid.
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


الحصول أو تعيين كائن مخصص لتسلسله إلى محتوى QR-Code.


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


الحصول أو تعيين كائن مخصص لتسلسله إلى محتوى QR-Code.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

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

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


الحصول أو تعيين العلامة للحصول على محتوى صورة QR-Code لتوقيع تم وضعه على صفحة المستند.
إذا تم تعيين هذه العلامة إلى true، سيحتفظ محتوى صورة توقيع QR-Code ببيانات الصورة الخام بالتنسيق المطلوب
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
بشكل افتراضي، هذا الخيار معطل.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


الحصول أو تعيين العلامة للحصول على محتوى صورة QR-Code لتوقيع تم وضعه على صفحة المستند.
إذا تم تعيين هذه العلامة إلى true، سيحتفظ محتوى صورة توقيع QR-Code ببيانات الصورة الخام بالتنسيق المطلوب
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


تحديد نوع الملف لمحتوى الصورة المرجعة لتوقيع QR-Code عندما تكون خاصية ReturnContent مفعلة.
بشكل افتراضي يتم تعيينه إلى Null. وهذا يعني إرجاع محتوى صورة QR-Code بالتنسيق الأصلي.
تم تحديد تنسيق الصورة هذا في
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
القيم المدعومة المحتملة هي: FileType.JPEG، FileType.PNG، FileType.BMP.
إذا كان التنسيق المقدم غير مدعوم فسيتم إرجاع محتوى صورة QR-Code بتنسيق .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


تحديد نوع الملف لمحتوى الصورة المرجعة لتوقيع QR-Code عندما تكون خاصية ReturnContent مفعلة.
بشكل افتراضي يتم تعيينه إلى Null. وهذا يعني إرجاع محتوى صورة QR-Code بالتنسيق الأصلي.
تم تحديد تنسيق الصورة هذا في
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
القيم المدعومة المحتملة هي: FileType.JPEG، FileType.PNG، FileType.BMP.
إذا كان التنسيق المقدم غير مدعوم فسيتم إرجاع محتوى صورة QR-Code بتنسيق .png.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
