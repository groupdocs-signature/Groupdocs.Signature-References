---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع حقل النموذج لإدخال النص لمستند Pdf."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

يحتوي على خصائص توقيع حقل النموذج لإدخال النص لمستند Pdf.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | ينشئ PdfTextFormFieldSignature باسم محدد مسبقًا. |
| [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | ينشئ PdfTextFormFieldSignature باسم محدد مسبقًا. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getText()](#getText--) | يحصل أو يعيّن نص حقل النموذج النصي. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يعيّن نص حقل النموذج النصي. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ كائن FormField Signature. |
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


ينشئ PdfTextFormFieldSignature باسم محدد مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


ينشئ PdfTextFormFieldSignature باسم محدد مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |
| نص | java.lang.String | نص كائن حقل النموذج. |

### getText() {#getText--}
```
public final String getText()
```


يحصل أو يعيّن نص حقل النموذج النصي.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحصل أو يعيّن نص حقل النموذج النصي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

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
