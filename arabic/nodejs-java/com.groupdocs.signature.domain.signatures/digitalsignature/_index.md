---
title: "DigitalSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص التوقيع الرقمي."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

يحتوي على خصائص التوقيع الرقمي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DigitalSignature()](#DigitalSignature--) | تهيئة التوقيع الرقمي باستخدام المعلمات الافتراضية. |
| [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | تهيئة التوقيع الرقمي باستخدام SignatureId المعروف. |
| [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | إنشاء توقيع رقمي باستخدام شهادة محددة. |
| [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | إنشاء توقيع رقمي بناءً على شهادة X509Certificate والمفتاح الخاص PrivateKey. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCertificate()](#getCertificate--) | يحصل أو يعيّن شهادة KeyStore. |
| [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | يحصل أو يعيّن شهادة KeyStore. |
| [getX509Certificate()](#getX509Certificate--) | يحصل أو يعيّن شهادة X509. |
| [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | يحصل أو يعيّن شهادة X509. |
| [getPrivateKey()](#getPrivateKey--) | يحصل أو يعيّن المفتاح الخاص PrivateKey للشهادة. |
| [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | يحصل أو يعيّن المفتاح الخاص PrivateKey للشهادة. |
| [getCertificateName()](#getCertificateName--) | يحصل أو يعيّن اسم شهادة X509. |
| [setCertificateName(String value)](#setCertificateName-java.lang.String-) | يحصل أو يعيّن اسم شهادة X509. |
| [getComments()](#getComments--) | يحصل أو يعيّن تعليق غرض التوقيع. |
| [setComments(String value)](#setComments-java.lang.String-) | يحصل أو يعيّن تعليق غرض التوقيع. |
| [isValid()](#isValid--) | يبقى true إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند. |
| [setValid(boolean value)](#setValid-boolean-) | يبقى true إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند. |
| [getSignTime()](#getSignTime--) | يحصل أو يعيّن وقت توقيع المستند. |
| [setSignTime(Date value)](#setSignTime-java.util.Date-) | يحصل أو يعيّن وقت توقيع المستند. |
| [getXAdESType()](#getXAdESType--) | نوع XAdES  XAdESType . |
| [setXAdESType(int value)](#setXAdESType-int-) | نوع XAdES  XAdESType . |
| [getThumbprint()](#getThumbprint--) | يحصل على بصمة شهادة. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ مثيل توقيع الباركود. |
| [loadDigitalSignatures()](#loadDigitalSignatures--) | تحميل التوقيع الرقمي من جميع مخازن شهادات X509 النظام. |
| [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | تحميل التوقيع الرقمي من مخزن شهادات X509 الممرَّر. |
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


تهيئة التوقيع الرقمي باستخدام المعلمات الافتراضية.

### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


تهيئة التوقيع الرقمي باستخدام SignatureId المعروف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


إنشاء توقيع رقمي باستخدام شهادة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| شهادة | java.security.KeyStore | شهادة X509. |

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


إنشاء توقيع رقمي بناءً على شهادة X509Certificate والمفتاح الخاص PrivateKey.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cert | java.security.cert.X509Certificate | شهادة X509Certificate. |
| المفتاح | java.security.PrivateKey | المفتاح الخاص للشهادة. |

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


يحصل أو يعيّن شهادة KeyStore.

**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


يحصل أو يعيّن شهادة KeyStore.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


يحصل أو يعيّن شهادة X509.

**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


يحصل أو يعيّن شهادة X509.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


يحصل أو يعيّن المفتاح الخاص PrivateKey للشهادة.

**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


يحصل أو يعيّن المفتاح الخاص PrivateKey للشهادة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


يحصل أو يعيّن اسم شهادة X509.

**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


يحصل أو يعيّن اسم شهادة X509.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


يحصل أو يعيّن تعليق غرض التوقيع.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


يحصل أو يعيّن تعليق غرض التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


يبقى true إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


يبقى true إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


يحصل أو يعيّن وقت توقيع المستند.

**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


يحصل أو يعيّن وقت توقيع المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


نوع XAdES  XAdESType . القيمة الافتراضية هي لا شيء (XAdES غير مفعل). في الوقت الحالي يتم دعم نوع توقيع XAdES فقط لمستندات الجداول الإلكترونية.

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


نوع XAdES  XAdESType . القيمة الافتراضية هي لا شيء (XAdES غير مفعل). في الوقت الحالي يتم دعم نوع توقيع XAdES فقط لمستندات الجداول الإلكترونية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


يحصل على بصمة شهادة.

**Returns:**
java.lang.String
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
### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


تحميل التوقيع الرقمي من جميع مخازن شهادات X509 النظام.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - يرجع قائمة من [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) التواقيع الرقمية.
### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


تحميل التوقيع الرقمي من مخزن شهادات X509 الممرَّر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - يرجع قائمة من [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) التواقيع الرقمية.
