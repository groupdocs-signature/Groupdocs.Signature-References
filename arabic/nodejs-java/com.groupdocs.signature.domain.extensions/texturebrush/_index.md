---
title: "TextureBrush"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل فرشاة نسيجية."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

يمثل فرشاة نسيجية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextureBrush()](#TextureBrush--) | يقوم بإنشاء نسخة جديدة من الفئة TextureBrush بالقيم الافتراضية. |
| [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | يقوم بإنشاء نسخة جديدة من الفئة TextureBrush باستخدام ملف الصورة. |
| [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | يقوم بإنشاء نسخة جديدة من الفئة TextureBrush مع خيار تدفق الصورة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | يحصل على أو يعيّن مسار ملف صورة النسيج. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | يحصل على أو يعيّن مسار ملف صورة النسيج. |
| [getImageStream()](#getImageStream--) | يحصل على أو يعيّن تدفق صورة النسيج. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | يحصل على أو يعيّن تدفق صورة النسيج. |
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


يقوم بإنشاء نسخة جديدة من الفئة TextureBrush بالقيم الافتراضية.

### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


يقوم بإنشاء نسخة جديدة من الفئة TextureBrush باستخدام ملف الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageFilePath | java.lang.String | مسار ملف الصورة. |

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


يقوم بإنشاء نسخة جديدة من الفئة TextureBrush مع خيار تدفق الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageStream | java.io.InputStream | تدفق الصورة. |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


يحصل على أو يعيّن مسار ملف صورة النسيج. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد ImageStream.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


يحصل على أو يعيّن مسار ملف صورة النسيج. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد ImageStream.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


يحصل على أو يعيّن تدفق صورة النسيج. إذا تم تحديد هذه الخاصية، يتم دائمًا استخدامها بدلاً من ImageFilePath.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


يحصل على أو يعيّن تدفق صورة النسيج. إذا تم تحديد هذه الخاصية، يتم دائمًا استخدامها بدلاً من ImageFilePath.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.io.InputStream |  |

