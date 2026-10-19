---
title: "TextFormFieldSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع حقل النموذج لإدخال النص لمستند PDF"
type: docs
weight: 15
url: /ar/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

يحتوي على خصائص توقيع حقل النموذج لإدخال النص لمستند PDF

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | ينشئ PdfTextFormFieldSignature مع اسم محدد مسبقًا. |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | ينشئ PdfTextFormFieldSignature مع اسم محدد مسبقًا. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | يحصل أو يعيّن نص إدخال حقل النموذج النصي. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يحصل أو يعيّن نص إدخال حقل النموذج النصي. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ نسخة من FormField Signature. |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


ينشئ PdfTextFormFieldSignature مع اسم محدد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


ينشئ PdfTextFormFieldSignature مع اسم محدد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|
|  | نص | java.lang.String | نص كائن حقل النموذج. |
|

### getText() {#getText--}
```
public final String getText()
```


يحصل أو يعيّن نص إدخال حقل النموذج النصي.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحصل أو يعيّن نص إدخال حقل النموذج النصي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

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


استنساخ نسخة من FormField Signature.


**Returns:**
java.lang.Object - يُرجع نسخة مستنسخة من FormField Signature.

