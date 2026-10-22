---
title: "ComboboxFormFieldSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع حقل النموذج لإدخال combo-box."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

يحتوي على خصائص توقيع حقل النموذج لإدخال combo-box.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا. |
| [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا وقائمة الخيارات. |
| [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا، وقائمة الخيارات، والقيمة المحددة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSelected()](#getSelected--) | احصل على القيمة المحددة أو عيّنها. |
| [setSelected(String value)](#setSelected-java.lang.String-) | احصل على القيمة المحددة أو عيّنها. |
| [getItems()](#getItems--) | احصل على قائمة خيارات combo-box أو عيّنها. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | احصل على قائمة خيارات combo-box أو عيّنها. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ كائن FormField Signature. |
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا وقائمة الخيارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |
| العناصر | java.util.List<java.lang.String> | قيم قائمة combo-box. |

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


ينشئ ComboboxFormFieldSignature باسم محدد مسبقًا، وقائمة الخيارات، والقيمة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن حقل النموذج. |
| العناصر | java.util.List<java.lang.String> | قيم قائمة combo-box. |
| المحدد | java.lang.Object | القيمة المحددة. |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


احصل على القيمة المحددة أو عيّنها.

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


احصل على القيمة المحددة أو عيّنها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


احصل على قائمة خيارات combo-box أو عيّنها.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


احصل على قائمة خيارات combo-box أو عيّنها.

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
