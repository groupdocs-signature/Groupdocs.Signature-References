---
title: "BarcodeSignOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات توقيع الباركود."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

يمثل خيارات توقيع الباركود.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | يُهيئ مثيلاً جديدًا من الفئة **BarcodeSignOptions** بالقيم الافتراضية. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | يُهيئ مثيلاً جديدًا من الفئة **BarcodeSignOptions** بالنص. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | يُهيئ مثيلاً جديدًا من الفئة **BarcodeSignOptions** بالنص. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | يحصل أو يعيّن نوع الباركود. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | يحصل أو يعيّن نوع الباركود. |
|
|  | [getForeColor()](#getForeColor--) | يحصل أو يعيّن اللون الأمامي لأشرطة الباركود |
استخدام هذه الخاصية قد يسبب مشاكل في التحقق.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | يحصل أو يعيّن اللون الأمامي لأشرطة الباركود |
استخدام هذه الخاصية قد يسبب مشاكل في التحقق.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | يحصل أو يعيّن اللون الأمامي لأشرطة الباركود |
استخدام هذه الخاصية قد يسبب مشاكل في التحقق.
|
|  | [getInnerMargins()](#getInnerMargins--) | يحصل أو يعيّن المسافة بين عناصر الباركود وحدود الصورة الناتجة. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | يحصل أو يعيّن المسافة بين عناصر الباركود وحدود الصورة الناتجة. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | يحصل أو يعيّن محاذاة النص في صورة الباركود الناتجة. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | يحصل أو يعيّن محاذاة النص في صورة الباركود الناتجة. |
|
|  | [getReturnContent()](#getReturnContent--) | يحصل أو يعيّن علامة للحصول على محتوى صورة الباركود لتوقيع تم وضعه على صفحة المستند. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | يحصل أو يعيّن علامة للحصول على محتوى صورة الباركود لتوقيع تم وضعه على صفحة المستند. |
|
|  | [getReturnContentType()](#getReturnContentType--) | يحدد نوع الملف لمحتوى الصورة المعاد لتوقيع الباركود عندما تكون خاصية ReturnContent مفعلة. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | يحدد نوع الملف لمحتوى الصورة المعاد لتوقيع الباركود عندما تكون خاصية ReturnContent مفعلة. |
|
|  | [validate()](#validate--) | طريقة داخلية للتحقق من معلمات خيارات الباركود. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


يُهيئ مثيلاً جديدًا من الفئة **BarcodeSignOptions** بالقيم الافتراضية.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


يُهيئ مثيلاً جديدًا من الفئة **BarcodeSignOptions** بالنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص الباركود |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


يُهيئ مثيلاً جديدًا من الفئة **BarcodeSignOptions** بالنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص الباركود |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | نوع ترميز الباركود انظر [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


يحصل أو يعيّن نوع الباركود.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


يحصل أو يعيّن نوع الباركود.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


يحصل أو يعيّن اللون الأمامي لأشرطة الباركود
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


يحصل أو يعيّن اللون الأمامي لأشرطة الباركود
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


يحصل أو يعيّن اللون الأمامي لأشرطة الباركود
استخدام هذه الخاصية قد يسبب مشاكل في التحقق. استخدمها بحذر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


يحصل أو يعيّن المسافة بين عناصر الباركود وحدود الصورة الناتجة.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


يحصل أو يعيّن المسافة بين عناصر الباركود وحدود الصورة الناتجة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


يحصل أو يعيّن محاذاة النص في صورة الباركود الناتجة.
القيمة الافتراضية هي None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


يحصل أو يعيّن محاذاة النص في صورة الباركود الناتجة.
القيمة الافتراضية هي None.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


يحصل أو يعيّن علامة للحصول على محتوى صورة الباركود لتوقيع تم وضعه على صفحة المستند.
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


يحصل أو يعيّن علامة للحصول على محتوى صورة الباركود لتوقيع تم وضعه على صفحة المستند.
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
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
القيم المدعومة المحتملة هي: FileType.JPEG، FileType.PNG، FileType.BMP.
إذا كان التنسيق المقدم غير مدعوم، سيتم إرجاع محتوى صورة الباركود بتنسيق .png.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


طريقة داخلية للتحقق من معلمات خيارات الباركود.


### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
