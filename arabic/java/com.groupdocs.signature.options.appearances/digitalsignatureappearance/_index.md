---
title: "DigitalSignatureAppearance"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يصف مظهر خط التوقيع للتوقيع الرقمي."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

يصف مظهر خط التوقيع للتوقيع الرقمي.
يمكن تطبيق سطر توقيع واحد على توقيع رقمي واحد فقط.
سطر التوقيع يكون دائمًا في الصفحة الأولى.
قد تكون هذه الميزة مفيدة لتنسيقات الملفات .docx و .doc و .odt و .xlsx.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | ينشئ كائن مظهر سطر التوقيع. |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مظهر سطر التوقيع بالقيم المحددة (الموقع، العنوان، البريد الإلكتروني). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSigner()](#getSigner--) | الحصول أو تعيين اسم الموقع لسطر التوقيع. |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | الحصول أو تعيين اسم الموقع لسطر التوقيع. |
|
|  | [getTitle()](#getTitle--) | الحصول أو تعيين عنوان لسطر التوقيع. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | الحصول أو تعيين عنوان لسطر التوقيع. |
|
|  | [getEmail()](#getEmail--) | الحصول أو تعيين بريد إلكتروني سيُعرض في سطر التوقيع. |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | الحصول أو تعيين بريد إلكتروني سيُعرض في سطر التوقيع. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


ينشئ كائن مظهر سطر التوقيع.


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


ينشئ مظهر سطر التوقيع بالقيم المحددة (الموقع، العنوان، البريد الإلكتروني).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الموقع | java.lang.String | اسم الموقع. |
|
|  | العنوان | java.lang.String | عنوان التوقيع. |
|
|  | البريد الإلكتروني | java.lang.String | البريد الإلكتروني للمؤلف. |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


الحصول أو تعيين اسم الموقع لسطر التوقيع.


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


الحصول أو تعيين اسم الموقع لسطر التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


الحصول أو تعيين عنوان لسطر التوقيع.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


الحصول أو تعيين عنوان لسطر التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


الحصول أو تعيين بريد إلكتروني سيُعرض في سطر التوقيع.


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


الحصول أو تعيين بريد إلكتروني سيُعرض في سطر التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
