---
title: "RadioButtonFormFieldSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع حقل النموذج لإدخال زر الراديو."
type: docs
weight: 14
url: /ar/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

يحتوي على خصائص توقيع حقل النموذج لإدخال زر الراديو.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | ينشئ RadioButtonFieldSignature باسم محدد مسبقًا. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | ينشئ RadioButtonFieldSignature مع اسم محدد مسبقًا وقائمة العناصر. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | ينشئ RadioButtonFieldSignature مع اسم محدد مسبقًا، قائمة العناصر والقيمة المحددة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSelected()](#getSelected--) | يحتوي على القيمة المحددة. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | يحتوي على القيمة المحددة. |
|
|  | [getItems()](#getItems--) | احصل أو عيّن قائمة خيارات أزرار الراديو. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | احصل أو عيّن قائمة خيارات أزرار الراديو. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ نسخة من FormField Signature. |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


ينشئ RadioButtonFieldSignature باسم محدد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


ينشئ RadioButtonFieldSignature مع اسم محدد مسبقًا وقائمة العناصر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|
|  | items | java.util.List<java.lang.String> | قيم قائمة أزرار الراديو. |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


ينشئ RadioButtonFieldSignature مع اسم محدد مسبقًا، قائمة العناصر والقيمة المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|
|  | items | java.util.List<java.lang.String> | قيم قائمة أزرار الراديو. |
|
|  | selected | java.lang.Object | القيمة المختارة. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


يحتوي على القيمة المحددة.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


يحتوي على القيمة المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


احصل أو عيّن قائمة خيارات أزرار الراديو.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


احصل أو عيّن قائمة خيارات أزرار الراديو.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.List<java.lang.String> |  |

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

