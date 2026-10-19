---
title: "CheckboxFormFieldSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع حقل النموذج لإدخال خانة الاختيار."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

يحتوي على خصائص توقيع حقل النموذج لإدخال خانة الاختيار.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | ينشئ PdfCheckboxFormFieldSignature باسم محدد مسبقًا. |
|
|  | [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | ينشئ PdfCheckboxFormFieldSignature باسم محدد مسبقًا وقيمة |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getChecked()](#getChecked--) | يحصل أو يضبط القيمة المحددة لحقل النموذج من نوع خانة اختيار. |
|
|  | [setChecked(boolean value)](#setChecked-boolean-) | يحصل أو يضبط القيمة المحددة لحقل النموذج من نوع خانة اختيار. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ نسخة من FormField Signature. |
|
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


ينشئ PdfCheckboxFormFieldSignature باسم محدد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


ينشئ PdfCheckboxFormFieldSignature باسم محدد مسبقًا وقيمة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|
|  | isChecked | boolean | القيمة إذا تم تحديد خانة الاختيار |
|

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


يحصل أو يضبط القيمة المحددة لحقل النموذج من نوع خانة اختيار.


**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


يحصل أو يضبط القيمة المحددة لحقل النموذج من نوع خانة اختيار.


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


استنساخ نسخة من FormField Signature.


**Returns:**
java.lang.Object - يُرجع نسخة مستنسخة من FormField Signature.

