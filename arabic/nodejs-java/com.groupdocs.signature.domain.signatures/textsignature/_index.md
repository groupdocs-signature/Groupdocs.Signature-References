---
title: "TextSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع النص."
type: docs
weight: 18
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

يحتوي على خصائص توقيع النص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | تهيئة كائن TextSignature بمعرف التوقيع الذي تم الحصول عليه بعد عملية البحث. |
| [TextSignature()](#TextSignature--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getText()](#getText--) | يحدد النص في التوقيع. |
| [setText(String value)](#setText-java.lang.String-) | يحدد النص في التوقيع. |
| [getSignatureImplementation()](#getSignatureImplementation--) | يحدد تنفيذ توقيع النص. |
| [getNative()](#getNative--) | يحدد السمة الأصلية. |
| [setNative(boolean value)](#setNative-boolean-) | يحدد السمة الأصلية. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ كائن Text Signature. |
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


تهيئة كائن TextSignature بمعرف التوقيع الذي تم الحصول عليه بعد عملية البحث. يُستخدم هذا المعرف الفريد للعثور على خصائص إضافية لهذا التوقيع من طبقة معلومات توقيع المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureId | java.lang.String | معرف توقيع فريد تم الحصول عليه بواسطة طريقة التوقيع أو البحث. |

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


يحدد السمة الأصلية. تكون true إذا كان التوقيع خاصًا بالمستند.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


يحدد السمة الأصلية. تكون true إذا كان التوقيع خاصًا بالمستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

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


استنساخ كائن Text Signature.

**Returns:**
java.lang.Object - يُرجِع نسخة مستنسخة من كائن Text Signature.
