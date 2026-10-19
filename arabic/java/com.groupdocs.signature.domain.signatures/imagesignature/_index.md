---
title: "ImageSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع الصورة."
type: docs
weight: 14
url: /ar/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

يحتوي على خصائص توقيع الصورة.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | تهيئة كائن ImageSignature بمعرف التوقيع الذي تم الحصول عليه بعد عملية البحث. |
|
|  | [ImageSignature()](#ImageSignature--) | تهيئة ImageSignature باستخدام المعلمات الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSize()](#getSize--) | يحدد حجم صورة التوقيع بالبايت. |
|
|  | [setSize(int value)](#setSize-int-) | يحدد حجم صورة التوقيع بالبايت. |
|
|  | [getFormat()](#getFormat--) | يحدد تنسيق صورة التوقيع. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | يحدد تنسيق صورة التوقيع. |
|
|  | [getContent()](#getContent--) | يحدد محتوى البيانات الثنائية للصورة من النوع |
التنسيق
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ نسخة توقيع الباركود. |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


تهيئة كائن ImageSignature بمعرف التوقيع الذي تم الحصول عليه بعد عملية البحث.
يُستخدم هذا المعرف الفريد للعثور على خصائص إضافية لهذا التوقيع من طبقة معلومات توقيع المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatureId | java.lang.String | معرف توقيع فريد يتم الحصول عليه بواسطة طريقة Sign أو Search من فئة Signature [Signature](../../com.groupdocs.signature/signature). |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


تهيئة ImageSignature باستخدام المعلمات الافتراضية.


### getSize() {#getSize--}
```
public final int getSize()
```


يحدد حجم صورة التوقيع بالبايت.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


يحدد حجم صورة التوقيع بالبايت.



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


يحدد تنسيق صورة التوقيع.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


يحدد تنسيق صورة التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


يحدد محتوى البيانات الثنائية للصورة من النوع
التنسيق
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
بشكل افتراضي، لن يتم تعيين هذه الخاصية.
استخدم الخاصية
ImageSearchOptions.ReturnContent
({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) لتمكين هذه الميزة.


**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


يستبدل طريقة Equals لمقارنة خصائص التوقيع


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التوقيع | java.lang.Object | كائن التوقيع للمقارنة معه. |
|

**Returns:**
boolean - يُعيد true إذا كان كائن التوقيع الممرّر له نفس النوع وجميع خصائصه مساوية لخصائص هذه الحالة.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يستبدل طريقة GetHashCode


**Returns:**
int - رمز التجزئة للتوقيع

### deepClone() {#deepClone--}
```
public Object deepClone()
```


استنساخ نسخة توقيع الباركود.


**Returns:**
java.lang.Object - يُعيد نسخة مستنسخة من كائن Barcode Signature.

