---
title: "TextSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع النص."
type: docs
weight: 18
url: /ar/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

يحتوي على خصائص توقيع النص.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | تهيئة كائن TextSignature بمعرّف التوقيع الذي تم الحصول عليه بعد عملية البحث. |
|
| [TextSignature()](#TextSignature--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | يحدد النص في التوقيع. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يحدد النص في التوقيع. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | يحدد تنفيذ توقيع النص. |
|
|  | [getNative()](#getNative--) | يحدد الخاصية الأصلية. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | يحدد الخاصية الأصلية. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ نسخة Text Signature. |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


تهيئة كائن TextSignature بمعرّف التوقيع الذي تم الحصول عليه بعد عملية البحث.
يُستخدم هذا المعرف الفريد للعثور على خصائص إضافية لهذا التوقيع من طبقة معلومات توقيع المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatureId | java.lang.String | معرّف التوقيع الفريد الذي يتم الحصول عليه بواسطة طريقة التوقيع أو البحث. |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


يحدد النص في التوقيع.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحدد النص في التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


يحدد تنفيذ توقيع النص.


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


يحدد السمة الأصلية. تكون true إذا كان التوقيع مخصصًا للمستند.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


يحدد السمة الأصلية. تكون true إذا كان التوقيع مخصصًا للمستند.


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


استنساخ نسخة Text Signature.


**Returns:**
java.lang.Object - يُرجِع نسخة مستنسخة من كائن Text Signature.

