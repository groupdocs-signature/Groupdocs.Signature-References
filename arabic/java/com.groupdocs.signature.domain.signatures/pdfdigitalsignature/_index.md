---
title: "PdfDigitalSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع PDF الرقمي."
type: docs
weight: 15
url: /ar/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

يحتوي على خصائص توقيع PDF الرقمي.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | تهيئة توقيع PDF الرقمي بدون شهادة. |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | إنشاء توقيع PDF الرقمي باستخدام شهادة محددة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | المعلومات المقدمة من الموقّع لتمكين المستلم من الاتصال بالموقّع |
للتحقق من التوقيع، على سبيل المثال.
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | المعلومات المقدمة من الموقّع لتمكين المستلم من الاتصال بالموقّع |
للتحقق من التوقيع، على سبيل المثال.
|
|  | [getLocation()](#getLocation--) | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
|
|  | [getReason()](#getReason--) | سبب التوقيع، مثل (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | سبب التوقيع، مثل (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [getType()](#getType--) | نوع توقيع PDF الرقمي. |
|
|  | [setType(int value)](#setType-int-) | نوع توقيع PDF الرقمي. |
|
|  | [getTimeStamp()](#getTimeStamp--) | الطابع الزمني لتوقيع PDF الرقمي. |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | الطابع الزمني لتوقيع PDF الرقمي. |
|
|  | [getShowProperties()](#getShowProperties--) | إجبار على إظهار/إخفاء خصائص التوقيع. |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | إجبار على إظهار/إخفاء خصائص التوقيع. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ نسخة توقيع الباركود. |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


تهيئة توقيع PDF الرقمي بدون شهادة.


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


إنشاء توقيع PDF الرقمي باستخدام شهادة محددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | شهادة | java.security.KeyStore | شهادة X509. |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


المعلومات المقدمة من الموقّع لتمكين المستلم من الاتصال بالموقّع
للتحقق من التوقيع، على سبيل المثال رقم هاتف.


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


المعلومات المقدمة من الموقّع لتمكين المستلم من الاتصال بالموقّع
للتحقق من التوقيع، على سبيل المثال رقم هاتف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


سبب التوقيع، مثل (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


سبب التوقيع، مثل (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


نوع توقيع PDF الرقمي.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


نوع توقيع PDF الرقمي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


الطابع الزمني لتوقيع PDF الرقمي.
القيمة الافتراضية هي null.


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


الطابع الزمني لتوقيع PDF الرقمي.
القيمة الافتراضية هي null.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


فرض إظهار/إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا التوقيع
الحقل له تنسيق مظهر محدد مسبقًا
تم التوقيع إلكترونيًا بواسطة {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} التاريخ: {Date} السبب: {
السبب
(#getReason.getReason/#setReason(String).setReason(String))}
الموقع: {
الموقع
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties صحيح بشكل افتراضي.


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


فرض إظهار/إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا التوقيع
الحقل له تنسيق مظهر محدد مسبقًا
تم التوقيع إلكترونيًا بواسطة {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} التاريخ: {Date} السبب: {
السبب
(#getReason.getReason/#setReason(String).setReason(String))}
الموقع: {
الموقع
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties صحيح بشكل افتراضي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

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

