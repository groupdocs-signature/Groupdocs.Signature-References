---
title: "RadioButtonFormFieldSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع حقل النموذج لإدخال radio-button."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

يحتوي على خصائص توقيع حقل النموذج لإدخال radio-button.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | ينشئ RadioButtonFieldSignature باسم محدد مسبقًا. |
| [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | ينشئ RadioButtonFieldSignature باسم محدد مسبقًا وقائمة العناصر. |
| [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | ينشئ RadioButtonFieldSignature باسم محدد مسبقًا، وقائمة العناصر، والقيمة المحددة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSelected()](#getSelected--) | يحتوي على القيمة المحددة. |
| [setSelected(String value)](#setSelected-java.lang.String-) | يحتوي على القيمة المحددة. |
| [getItems()](#getItems--) | احصل على قائمة خيارات أزرار الراديو أو عيّنها. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | احصل على قائمة خيارات أزرار الراديو أو عيّنها. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ كائن FormField Signature. |
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


ينشئ RadioButtonFieldSignature باسم محدد مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


ينشئ RadioButtonFieldSignature باسم محدد مسبقًا وقائمة العناصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |
| العناصر | java.util.List<java.lang.String> | قيم قائمة أزرار الراديو. |

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


ينشئ RadioButtonFieldSignature باسم محدد مسبقًا، وقائمة العناصر، والقيمة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |
| العناصر | java.util.List<java.lang.String> | قيم قائمة أزرار الراديو. |
| المحدد | java.lang.Object | القيمة المحددة. |

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


احصل على قائمة خيارات أزرار الراديو أو عيّنها.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


احصل على قائمة خيارات أزرار الراديو أو عيّنها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.List<java.lang.String> |  |

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
