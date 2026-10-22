---
title: "CheckboxFormFieldSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع حقل النموذج لإدخال check-box."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

يحتوي على خصائص توقيع حقل النموذج لإدخال check-box.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | ينشئ PdfCheckboxFormFieldSignature باسم محدد مسبقًا. |
| [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | ينشئ PdfCheckboxFormFieldSignature باسم وقيمة محددين مسبقًا |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChecked()](#getChecked--) | يحصل أو يعيّن القيمة المحددة لمدخل خانة الاختيار لحقل النموذج. |
| [setChecked(boolean value)](#setChecked-boolean-) | يحصل أو يعيّن القيمة المحددة لمدخل خانة الاختيار لحقل النموذج. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ كائن FormField Signature. |
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


ينشئ PdfCheckboxFormFieldSignature باسم محدد مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


ينشئ PdfCheckboxFormFieldSignature باسم وقيمة محددين مسبقًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |
| isChecked | boolean | القيمة إذا تم تحديد خانة الاختيار |

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


يحصل أو يعيّن القيمة المحددة لمدخل خانة الاختيار لحقل النموذج.

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


يحصل أو يعيّن القيمة المحددة لمدخل خانة الاختيار لحقل النموذج.

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


استنساخ كائن FormField Signature.

**Returns:**
java.lang.Object - يُرجع نسخة مستنسخة من كائن FormField Signature.
