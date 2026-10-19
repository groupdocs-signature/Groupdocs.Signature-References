---
title: "DigitalSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص التوقيع الرقمي."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

يحتوي على خصائص التوقيع الرقمي.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | تهيئة التوقيع الرقمي باستخدام المعلمات الافتراضية. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | تهيئة التوقيع الرقمي بمعرف SignatureId المعروف. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | إنشاء توقيع رقمي باستخدام شهادة محددة. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | إنشاء توقيع رقمي استنادًا إلى شهادة X509Certificate والمفتاح الخاص PrivateKey. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | يحصل أو يعيّن شهادة KeyStore. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | يحصل أو يعيّن شهادة KeyStore. |
|
|  | [getX509Certificate()](#getX509Certificate--) | يحصل أو يضبط شهادة X509. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | يحصل أو يضبط شهادة X509. |
|
|  | [getPrivateKey()](#getPrivateKey--) | يحصل أو يضبط PrivateKey للشهادة. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | يحصل أو يضبط PrivateKey للشهادة. |
|
|  | [getCertificateName()](#getCertificateName--) | يحصل أو يضبط اسم شهادة X509. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | يحصل أو يضبط اسم شهادة X509. |
|
|  | [getComments()](#getComments--) | يحصل أو يضبط تعليق غرض التوقيع. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | يحصل أو يضبط تعليق غرض التوقيع. |
|
|  | [isValid()](#isValid--) | يبقى true إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | يبقى true إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند. |
|
|  | [getSignTime()](#getSignTime--) | يحصل أو يضبط وقت توقيع المستند. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | يحصل أو يضبط وقت توقيع المستند. |
|
|  | [getXAdESType()](#getXAdESType--) | نوع XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | نوع XAdES |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | يحصل على بصمة شهادة. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ نسخة توقيع الباركود. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | تحميل التوقيع الرقمي من جميع مخازن شهادات X509 النظامية. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | تحميل التوقيع الرقمي من مخزن شهادات X509 الممرَّر. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


تهيئة التوقيع الرقمي باستخدام المعلمات الافتراضية.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


تهيئة التوقيع الرقمي بمعرف SignatureId المعروف.


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
|  | شهادة | java.security.KeyStore | شهادة X509. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


إنشاء توقيع رقمي استنادًا إلى شهادة X509Certificate والمفتاح الخاص PrivateKey.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | شهادة X509Certificate. |
|
|  | key | java.security.PrivateKey | PrivateKey للشهادة. |
|

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


يحصل أو يضبط شهادة X509.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


يحصل أو يضبط شهادة X509.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


يحصل أو يضبط PrivateKey للشهادة.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


يحصل أو يضبط PrivateKey للشهادة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


يحصل أو يضبط اسم شهادة X509.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


يحصل أو يضبط اسم شهادة X509.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


يحصل أو يضبط تعليق غرض التوقيع.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


يحصل أو يضبط تعليق غرض التوقيع.


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


يحصل أو يضبط وقت توقيع المستند.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


يحصل أو يضبط وقت توقيع المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


نوع XAdES
XAdESType
. القيمة الافتراضية هي None (XAdES غير مفعَّل).
في الوقت الحالي يتم دعم نوع توقيع XAdES فقط للمستندات Spreadsheet.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


نوع XAdES
XAdESType
. القيمة الافتراضية هي None (XAdES غير مفعَّل).
في الوقت الحالي يتم دعم نوع توقيع XAdES فقط للمستندات Spreadsheet.


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

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


تحميل التوقيع الرقمي من جميع مخازن شهادات X509 النظامية.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - يُعيد قائمة من [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) التوقيعات الرقمية.

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
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - يُعيد قائمة من [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) التوقيعات الرقمية.

