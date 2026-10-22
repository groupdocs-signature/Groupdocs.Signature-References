---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع رمز الاستجابة السريعة."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

يحتوي على خصائص توقيع رمز الاستجابة السريعة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | تهيئة كائن QrCodeSignature بمعرف التوقيع الذي تم الحصول عليه بعد عملية البحث. |
| [QrCodeSignature()](#QrCodeSignature--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | يحدد نوع ترميز QR-code. |
| [getText()](#getText--) | يحدد نص QR-code. |
| [getFormat()](#getFormat--) | يحدد تنسيق صورة توقيع QR-code. |
| [getContent()](#getContent--) | يحدد محتوى صورة البيانات الثنائية لـ QR-code من النوع Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | الحصول على كائن من نص توقيع QR-Code عبر عملية فك التسلسل. |
| [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | الحصول على كائن من نص توقيع QR-Code عبر عملية فك التسلسل. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ نسخة توقيع QR-Code. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


تهيئة كائن QrCodeSignature بمعرف التوقيع الذي تم الحصول عليه بعد عملية البحث. يُستخدم هذا المعرف الفريد للعثور على خصائص إضافية لهذا التوقيع من طبقة معلومات توقيع المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureId | java.lang.String | معرف توقيع فريد تم الحصول عليه بواسطة طريقة التوقيع أو البحث. |

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


يحدد نوع ترميز QR-code.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


يحدد نص QR-code.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


يحدد تنسيق صورة توقيع QR-code.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


يحدد محتوى صورة البيانات الثنائية لـ QR-code من النوع Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). بشكل افتراضي لن يتم تعيين هذه الخاصية. استخدم الخاصية QrCodeSearchOptions.ReturnContent ([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#setReturnContent-boolean-)) لتمكين هذه الميزة.

**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


الحصول على كائن من نص توقيع QR-Code عبر عملية فك التسلسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | java.lang.Class<T> |  |

**Returns:**
T -  T : نوع الكائن لفك التسلسل من نص QR-Code
### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


الحصول على كائن من نص توقيع QR-Code عبر عملية فك التسلسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | تعيين تنفيذ تشفير البيانات المخصص |

T : نوع الكائن لفك التسلسل من نص QR-Code |
| نوع | java.lang.Class<T> |  |

**Returns:**
T -
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


استنساخ نسخة توقيع QR-Code.

**Returns:**
java.lang.Object - يرجع نسخة مستنسخة من توقيع QR-code.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| صورة | java.awt.image.BufferedImage |  |

