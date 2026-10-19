---
title: "DigitalSignOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات التوقيع الرقمي."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

يمثل خيارات التوقيع الرقمي.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بالقيم الافتراضية. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بملف الشهادة. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بتدفق الشهادة. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بملف الشهادة وملف الصورة. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بملف الشهادة وتدفق الصورة. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بتدفق الشهادة وملف الصورة. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بتدفق الشهادة وتدفق الصورة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getReason()](#getReason--) | يحصل أو يضبط سبب التوقيع. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | يحصل أو يضبط سبب التوقيع. |
|
|  | [getContact()](#getContact--) | يحصل أو يضبط جهة اتصال التوقيع. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | يحصل أو يضبط جهة اتصال التوقيع. |
|
|  | [getLocation()](#getLocation--) | يحصل أو يضبط موقع التوقيع. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | يحصل أو يضبط موقع التوقيع. |
|
|  | [getPassword()](#getPassword--) | يحصل أو يضبط كلمة مرور الشهادة الرقمية. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يحصل أو يضبط كلمة مرور الشهادة الرقمية. |
|
|  | [getSignature()](#getSignature--) | يحصل أو يعيّن خصائص توقيع المستند الرقمي. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | يحصل أو يعيّن خصائص توقيع المستند الرقمي. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | يحصل أو يعيّن مسار ملف الشهادة الرقمية. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | يحصل أو يعيّن معرف GUID لملف الشهادة الرقمية. |
|
|  | [getCertificateStream()](#getCertificateStream--) | يحصل أو يعيّن تدفق الشهادة الرقمية. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | يحصل أو يعيّن تدفق الشهادة الرقمية. |
|
|  | [getVisible()](#getVisible--) | يحصل أو يعيّن رؤية التوقيع. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | يحصل أو يعيّن رؤية التوقيع. |
|
|  | [getUseLtv()](#getUseLtv--) | يحصل/يعيّن علم التحقق LTV (التحقق طويل الأمد). |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | يحصل/يعيّن علم التحقق LTV (التحقق طويل الأمد). |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | يحصل أو يعيّن تنفيذ مخصص لتوقيع التجزئة، مما يسمح للمتصلين بإدماج الخاص بهم |
منطق التوقيع الرقمي (HSM، موقع بعيد، مخزن مفاتيح برمجي، إلخ).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | يعيّن تنفيذ مخصص لتوقيع التجزئة، مما يسمح للمتصلين بإدماج الخاص بهم |
منطق التوقيع الرقمي.
|
|  | [getXAdESType()](#getXAdESType--) | نوع XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | نوع XAdES |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بالقيم الافتراضية.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بملف الشهادة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | مسار ملف الشهادة الرقمية |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بتدفق الشهادة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | تدفق الشهادة الرقمية |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بملف الشهادة وملف الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | مسار ملف الشهادة الرقمية |
|
|  | imageFilePath | java.lang.String | مسار ملف صورة مظهر التوقيع |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بملف الشهادة وتدفق الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | مسار ملف الشهادة الرقمية |
|
|  | appearenceImageStream | java.io.InputStream | تدفق صورة مظهر التوقيع |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بتدفق الشهادة وملف الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | تدفق الشهادة الرقمية |
|
|  | imageFilePath | java.lang.String | مسار ملف صورة مظهر التوقيع |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


ينشئ مثيلًا جديدًا من الفئة DigitalSignOptions بتدفق الشهادة وتدفق الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | تدفق الشهادة الرقمية |
|
|  | appearenceImageStream | java.io.InputStream | تدفق صورة مظهر التوقيع |
|

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


يحصل أو يعيّن خصائص توقيع المستند الرقمي.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


يحصل أو يعيّن خصائص توقيع المستند الرقمي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


يحصل أو يعيّن مسار ملف الشهادة الرقمية.
يُستخدم هذا الخاصية فقط إذا لم يتم تحديد CertificateStream.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


يحصل أو يعيّن معرف GUID لملف الشهادة الرقمية.
يُستخدم هذا الخاصية فقط إذا لم يتم تحديد CertificateStream.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


يحصل أو يعيّن تدفق الشهادة الرقمية.
إذا تم تحديد هذه الخاصية، فستُستخدم دائمًا بدلاً من CertificateGuid.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


يحصل أو يعيّن تدفق الشهادة الرقمية.
إذا تم تحديد هذه الخاصية، فستُستخدم دائمًا بدلاً من CertificateGuid.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


يحصل أو يعيّن رؤية التوقيع.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


يحصل أو يعيّن رؤية التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


يحصل/يعيّن علم التحقق LTV (التحقق طويل الأمد).


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


يحصل/يعيّن علم التحقق LTV (التحقق طويل الأمد).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


يحصل أو يعيّن تنفيذ مخصص لتوقيع التجزئة، مما يسمح للمتصلين بإدماج الخاص بهم
منطق التوقيع الرقمي (HSM، موقع بعيد، مخزن مفاتيح برمجي، إلخ).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


يعيّن تنفيذ مخصص لتوقيع التجزئة، مما يسمح للمتصلين بإدماج الخاص بهم
منطق التوقيع الرقمي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


نوع XAdES
XAdESType
. القيمة الافتراضية هي None (XAdES غير مفعَّل).
في الوقت الحالي، يتم دعم نوع توقيع XAdES فقط لمستندات جداول البيانات تحت .NET Framework (ليس تحت .NET Standard).


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


نوع XAdES
XAdESType
. القيمة الافتراضية هي None (XAdES غير مفعَّل).
في الوقت الحالي، يتم دعم نوع توقيع XAdES فقط لمستندات جداول البيانات تحت .NET Framework (ليس تحت .NET Standard).


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
