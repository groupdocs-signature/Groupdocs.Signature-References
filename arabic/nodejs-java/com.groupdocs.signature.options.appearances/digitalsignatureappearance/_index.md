---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يصف مظهر خط التوقيع للتوقيع الرقمي."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

يصف مظهر خط التوقيع للتوقيع الرقمي. يمكن تطبيق خط توقيع واحد على توقيع رقمي واحد فقط. يكون خط التوقيع دائمًا في الصفحة الأولى. قد تكون هذه الميزة مفيدة لتنسيقات الملفات .docx و .doc و .odt و .xlsx.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | ينشئ كائن مظهر خط التوقيع. |
| [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مظهر خط التوقيع بالقيم المحددة (الموقع، العنوان، البريد الإلكتروني). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSigner()](#getSigner--) | يحصل أو يضبط اسم الموقع لخط التوقيع. |
| [setSigner(String value)](#setSigner-java.lang.String-) | يحصل أو يضبط اسم الموقع لخط التوقيع. |
| [getTitle()](#getTitle--) | يحصل أو يضبط عنوانًا لخط التوقيع. |
| [setTitle(String value)](#setTitle-java.lang.String-) | يحصل أو يضبط عنوانًا لخط التوقيع. |
| [getEmail()](#getEmail--) | يحصل أو يضبط بريدًا إلكترونيًا سيتم عرضه في خط التوقيع. |
| [setEmail(String value)](#setEmail-java.lang.String-) | يحصل أو يضبط بريدًا إلكترونيًا سيتم عرضه في خط التوقيع. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


ينشئ كائن مظهر خط التوقيع.

### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


ينشئ مظهر خط التوقيع بالقيم المحددة (الموقع، العنوان، البريد الإلكتروني).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الموقع | java.lang.String | اسم الموقع. |
| العنوان | java.lang.String | عنوان التوقيع. |
| البريد الإلكتروني | java.lang.String | البريد الإلكتروني للمؤلف. |

### getSigner() {#getSigner--}
```
public final String getSigner()
```


يحصل أو يضبط اسم الموقع لخط التوقيع.

**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


يحصل أو يضبط اسم الموقع لخط التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


يحصل أو يضبط عنوانًا لخط التوقيع.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


يحصل أو يضبط عنوانًا لخط التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


يحصل أو يضبط بريدًا إلكترونيًا سيتم عرضه في خط التوقيع.

**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


يحصل أو يضبط بريدًا إلكترونيًا سيتم عرضه في خط التوقيع.

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
