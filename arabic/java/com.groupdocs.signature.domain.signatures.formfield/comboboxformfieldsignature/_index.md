---
title: "ComboboxFormFieldSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع حقل النموذج لإدخال صندوق القوائم."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

يحتوي على خصائص توقيع حقل النموذج لإدخال صندوق القوائم.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا وقائمة خيارات. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا، قائمة خيارات والقيمة المختارة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSelected()](#getSelected--) | احصل أو اضبط القيمة المختارة. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | احصل أو اضبط القيمة المختارة. |
|
|  | [getItems()](#getItems--) | احصل أو اضبط قائمة خيارات صندوق الجمع. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | احصل أو اضبط قائمة خيارات صندوق الجمع. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ نسخة من FormField Signature. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا وقائمة خيارات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|
|  | items | java.util.List<java.lang.String> | قيم قائمة صندوق الجمع. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا، قائمة خيارات والقيمة المختارة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن حقل النموذج. |
|
|  | items | java.util.List<java.lang.String> | قيم قائمة صندوق الجمع. |
|
|  | selected | java.lang.Object | القيمة المختارة. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


احصل أو اضبط القيمة المختارة.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


احصل أو اضبط القيمة المختارة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


احصل أو اضبط قائمة خيارات صندوق الجمع.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


احصل أو اضبط قائمة خيارات صندوق الجمع.


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

