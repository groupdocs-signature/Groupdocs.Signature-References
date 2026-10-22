---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع الباركود."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

يحتوي على خصائص توقيع الباركود.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | تهيئة كائن BarcodeSignature بمعرف التوقيع الذي تم الحصول عليه بعد عملية البحث. |
| [BarcodeSignature()](#BarcodeSignature--) | تهيئة BarcodeSignature بالمعلمات الافتراضية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | يحدد نوع ترميز الباركود. |
| [getText()](#getText--) | يحدد نص الباركود. |
| [getFormat()](#getFormat--) | يحدد تنسيق صورة توقيع الباركود. |
| [getContent()](#getContent--) | يحدد محتوى صورة البيانات الثنائية للباركود من النوع Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ مثيل توقيع الباركود. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


تهيئة كائن BarcodeSignature بمعرف التوقيع الذي تم الحصول عليه بعد عملية البحث. يُستخدم هذا المعرف الفريد للعثور على خصائص إضافية لهذا التوقيع من طبقة معلومات توقيع المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureId | java.lang.String | معرّف التوقيع الفريد الذي تم الحصول عليه بواسطة طريقة Sign أو Search من فئة Signature [Signature](../../com.groupdocs.signature/signature). |

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


تهيئة BarcodeSignature بالمعلمات الافتراضية.

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


يحدد نوع ترميز الباركود.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


يحدد نص الباركود.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


يحدد تنسيق صورة توقيع الباركود.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


يحدد محتوى صورة البيانات الثنائية للباركود من النوع Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). بشكل افتراضي لن يتم تعيين هذه الخاصية. استخدم الخاصية BarcodeSearchOptions.ReturnContent ([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions\#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions\#setReturnContent-boolean-)) لتمكين هذه الميزة.

**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


يستبدل طريقة Equals لمقارنة خصائص التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| توقيع | java.lang.Object | كائن التوقيع للمقارنة معه. |

**Returns:**
boolean - يُرجِع true إذا كان كائن التوقيع الممرّر من نفس النوع وجميع خصائصه مساوية لخصائص هذا الكائن.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يتجاوز طريقة GetHashCode

**Returns:**
int - رمز التجزئة للتوقيع
### deepClone() {#deepClone--}
```
public Object deepClone()
```


استنساخ مثيل توقيع الباركود.

**Returns:**
java.lang.Object - يُرجِع نسخة مستنسخة من كائن Barcode Signature.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| صورة | java.awt.image.BufferedImage |  |

