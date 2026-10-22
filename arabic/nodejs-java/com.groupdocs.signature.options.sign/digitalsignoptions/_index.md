---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات التوقيع الرقمي."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

يمثل خيارات التوقيع الرقمي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DigitalSignOptions()](#DigitalSignOptions--) | ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بالقيم الافتراضية. |
| [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بملف الشهادة. |
| [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بتدفق الشهادة. |
| [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بملف الشهادة وملف الصورة. |
| [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بملف الشهادة وتدفق الصورة. |
| [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بتدفق الشهادة وملف الصورة. |
| [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بتدفق الشهادة وتدفق الصورة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getReason()](#getReason--) | يحصل أو يضبط سبب التوقيع. |
| [setReason(String value)](#setReason-java.lang.String-) | يحصل أو يضبط سبب التوقيع. |
| [getContact()](#getContact--) | يحصل أو يضبط جهة اتصال التوقيع. |
| [setContact(String value)](#setContact-java.lang.String-) | يحصل أو يضبط جهة اتصال التوقيع. |
| [getLocation()](#getLocation--) | يحصل أو يضبط موقع التوقيع. |
| [setLocation(String value)](#setLocation-java.lang.String-) | يحصل أو يضبط موقع التوقيع. |
| [getPassword()](#getPassword--) | يحصل أو يضبط كلمة مرور الشهادة الرقمية. |
| [setPassword(String value)](#setPassword-java.lang.String-) | يحصل أو يضبط كلمة مرور الشهادة الرقمية. |
| [getSignature()](#getSignature--) | يحصل أو يضبط خصائص توقيع المستند الرقمي. |
| [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | يحصل أو يضبط خصائص توقيع المستند الرقمي. |
| [getCertificateFilePath()](#getCertificateFilePath--) | يحصل أو يضبط مسار ملف الشهادة الرقمية. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | يحصل أو يضبط معرف GUID لملف الشهادة الرقمية. |
| [getCertificateStream()](#getCertificateStream--) | يحصل أو يضبط تدفق الشهادة الرقمية. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | يحصل أو يضبط تدفق الشهادة الرقمية. |
| [getVisible()](#getVisible--) | الحصول أو تعيين رؤية التوقيع. |
| [setVisible(boolean value)](#setVisible-boolean-) | الحصول أو تعيين رؤية التوقيع. |
| [getXAdESType()](#getXAdESType--) | نوع XAdES  XAdESType . |
| [setXAdESType(int value)](#setXAdESType-int-) | نوع XAdES  XAdESType . |
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بالقيم الافتراضية.

### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بملف الشهادة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateFilePath | java.lang.String | مسار ملف الشهادة الرقمية |

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بتدفق الشهادة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateStream | java.io.InputStream | دفق الشهادة الرقمية |

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بملف الشهادة وملف الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateFilePath | java.lang.String | مسار ملف الشهادة الرقمية |
| imageFilePath | java.lang.String | مسار ملف صورة مظهر التوقيع |

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بملف الشهادة وتدفق الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateFilePath | java.lang.String | مسار ملف الشهادة الرقمية |
| appearenceImageStream | java.io.InputStream | دفق صورة مظهر التوقيع |

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بتدفق الشهادة وملف الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateStream | java.io.InputStream | دفق الشهادة الرقمية |
| imageFilePath | java.lang.String | مسار ملف صورة مظهر التوقيع |

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


ينشئ مثيلاً جديدًا لفئة DigitalSignOptions بتدفق الشهادة وتدفق الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateStream | java.io.InputStream | دفق الشهادة الرقمية |
| appearenceImageStream | java.io.InputStream | دفق صورة مظهر التوقيع |

### getReason() {#getReason--}
```
public final String getReason()
```


يحصل أو يضبط سبب التوقيع.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


يحصل أو يضبط سبب التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


يحصل أو يضبط جهة اتصال التوقيع.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


يحصل أو يضبط جهة اتصال التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


يحصل أو يضبط موقع التوقيع.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


يحصل أو يضبط موقع التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل أو يضبط كلمة مرور الشهادة الرقمية.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يحصل أو يضبط كلمة مرور الشهادة الرقمية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


يحصل أو يضبط خصائص توقيع المستند الرقمي.

**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


يحصل أو يضبط خصائص توقيع المستند الرقمي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


الحصول أو تعيين مسار ملف الشهادة الرقمية. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد CertificateStream.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


الحصول أو تعيين معرف GUID لملف الشهادة الرقمية. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد CertificateStream.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


الحصول أو تعيين دفق الشهادة الرقمية. إذا تم تحديد هذه الخاصية فستُستخدم دائمًا بدلاً من CertificateGuid.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


الحصول أو تعيين دفق الشهادة الرقمية. إذا تم تحديد هذه الخاصية فستُستخدم دائمًا بدلاً من CertificateGuid.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


الحصول أو تعيين رؤية التوقيع.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


الحصول أو تعيين رؤية التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


نوع XAdES  XAdESType . القيمة الافتراضية هي None (XAdES غير مفعل). في الوقت الحالي يتم دعم نوع توقيع XAdES فقط لمستندات Spreadsheet تحت .NET Framework فقط (ليس تحت .NET Standard).

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


نوع XAdES  XAdESType . القيمة الافتراضية هي None (XAdES غير مفعل). في الوقت الحالي يتم دعم نوع توقيع XAdES فقط لمستندات Spreadsheet تحت .NET Framework فقط (ليس تحت .NET Standard).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.

**Returns:**
java.lang.String -
