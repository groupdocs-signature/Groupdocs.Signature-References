---
title: "LoadOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يسمح بتحديد خيارات إضافية مثل كلمة المرور عند فتح مستند للتوقيع."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

يسمح بتحديد خيارات إضافية (مثل كلمة المرور) عند فتح مستند للتوقيع.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | يقوم بتهيئة نسخة جديدة من الفئة LoadOptions. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يحصل على كلمة المرور أو يضبطها لفتح مستند محمي. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يحصل على كلمة المرور أو يضبطها لفتح مستند محمي. |
|
|  | [getLoadExternalResources()](#getLoadExternalResources--) | يحصل على الخيارات أو يضبطها التي تحدد ما إذا كان يجب تحميل موارد المستند الخارجية. |
|
|  | [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | يحصل على الخيارات أو يضبطها التي تحدد ما إذا كان يجب تحميل موارد المستند الخارجية. |
|
|  | [getPermissions()](#getPermissions--) | أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | مُعيّن داخلي، يُستخدم بواسطة معالجات تحميل المستند لتسجيل الأذونات المستخرجة من الملف. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


يقوم بتهيئة نسخة جديدة من الفئة LoadOptions.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل على كلمة المرور أو يضبطها لفتح مستند محمي.
سيُستخدم أيضاً لحفظ المستند الموقّع كحماية.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يحصل على كلمة المرور أو يضبطها لفتح مستند محمي.
سيُستخدم أيضاً لحفظ المستند الموقّع كحماية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


يحصل على الخيارات أو يضبطها التي تحدد ما إذا كان يجب تحميل موارد المستند الخارجية.
هذا الخيار مع القيمة المعطلة (false) يسمح بتوفير وقت التحميل للمستندات التي تحتوي على روابط موارد خارجية كثيرة أو كبيرة.
القيمة الافتراضية مفعّلة (true).


**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


يحصل على الخيارات أو يضبطها التي تحدد ما إذا كان يجب تحميل موارد المستند الخارجية.
هذا الخيار مع القيمة المعطلة (false) يسمح بتوفير وقت التحميل للمستندات التي تحتوي على روابط موارد خارجية كثيرة أو كبيرة.
القيمة الافتراضية مفعّلة (true).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات.
فقط لمستندات PDF. للقراءة فقط \\u2014 يتم تعبئتها تلقائيًا أثناء تحميل المستند.
القيمة هي تركيبة من العلامات من [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


مُعيّن داخلي، يُستخدم بواسطة معالجات تحميل المستند لتسجيل الأذونات المستخرجة من الملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Integer |  |

