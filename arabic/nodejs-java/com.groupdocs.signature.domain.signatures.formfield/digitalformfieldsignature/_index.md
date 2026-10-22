---
title: "DigitalFormFieldSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص حقل النموذج لإدخال التوقيع الرقمي لمستندات Pdf."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

يحتوي على خصائص حقل النموذج لإدخال التوقيع الرقمي لمستندات Pdf.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | ينشئ PdfDigitalFormFieldSignature باسم محدد مسبقًا. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSigned()](#getSigned--) | خاصية للقراءة فقط تُظهر ما إذا كان Form-field Signature موقّعًا بشهادة رقمية. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ كائن FormField Signature. |
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


ينشئ PdfDigitalFormFieldSignature باسم محدد مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


خاصية للقراءة فقط تُظهر ما إذا كان Form-field Signature موقّعًا بشهادة رقمية.

**Returns:**
boolean
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


استنساخ كائن FormField Signature.

**Returns:**
java.lang.Object - يُرجع نسخة مستنسخة من كائن FormField Signature.
