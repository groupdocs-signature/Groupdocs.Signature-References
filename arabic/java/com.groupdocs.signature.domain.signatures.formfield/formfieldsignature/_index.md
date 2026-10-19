---
title: "FormFieldSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع حقل النموذج."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

يحتوي على خصائص توقيع حقل النموذج.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يحدد اسم حقل النموذج الفريد. |
|
|  | [setName(String value)](#setName-java.lang.String-) | يحدد اسم حقل النموذج الفريد. |
|
|  | [getType()](#getType--) | يحدد نوع حقل النموذج. |
|
|  | [getValue()](#getValue--) | يحدد كائن بيانات حقل النموذج. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | يحدد كائن بيانات حقل النموذج. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ نسخة من FormField Signature. |
|
### getName() {#getName--}
```
public final String getName()
```


يحدد اسم حقل النموذج الفريد.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحدد اسم حقل النموذج الفريد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


يحدد نوع حقل النموذج.


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


يحدد كائن بيانات حقل النموذج.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


يحدد كائن بيانات حقل النموذج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

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

