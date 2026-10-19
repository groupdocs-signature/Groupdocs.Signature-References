---
title: "TextureBrush"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل فرشاة النسيج."
type: docs
weight: 14
url: /ar/java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

يمثل فرشاة النسيج.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [TextureBrush()](#TextureBrush--) | ينشئ مثيلاً جديداً من فئة TextureBrush بالقيم الافتراضية. |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | ينشئ مثيلاً جديداً من فئة TextureBrush بملف صورة. |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | ينشئ مثيلاً جديداً من فئة TextureBrush بخيار تدفق الصورة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | الحصول أو تعيين مسار ملف صورة النسيج. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | الحصول أو تعيين مسار ملف صورة النسيج. |
|
|  | [getImageStream()](#getImageStream--) | يحصل أو يضبط تدفق صورة القوام. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | يحصل أو يضبط تدفق صورة القوام. |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


ينشئ مثيلاً جديداً من فئة TextureBrush بالقيم الافتراضية.


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


ينشئ مثيلاً جديداً من فئة TextureBrush بملف صورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | مسار ملف الصورة. |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


ينشئ مثيلاً جديداً من فئة TextureBrush بخيار تدفق الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | تدفق الصورة. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


الحصول أو تعيين مسار ملف صورة النسيج.
تُستخدم هذه الخاصية فقط إذا لم يتم تحديد ImageStream.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


الحصول أو تعيين مسار ملف صورة النسيج.
تُستخدم هذه الخاصية فقط إذا لم يتم تحديد ImageStream.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


يحصل أو يضبط تدفق صورة القوام.
إذا تم تحديد هذه الخاصية، فستُستخدم دائمًا بدلاً من ImageFilePath.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


يحصل أو يضبط تدفق صورة القوام.
إذا تم تحديد هذه الخاصية، فستُستخدم دائمًا بدلاً من ImageFilePath.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.io.InputStream |  |

