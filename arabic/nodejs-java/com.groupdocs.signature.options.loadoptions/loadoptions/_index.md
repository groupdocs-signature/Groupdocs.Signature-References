---
title: "LoadOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يسمح بتحديد خيارات إضافية مثل كلمة المرور عند فتح مستند للتوقيع."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

يسمح بتحديد خيارات إضافية (مثل كلمة المرور) عند فتح مستند للتوقيع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | ينشئ مثيلاً جديداً من فئة LoadOptions. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPassword()](#getPassword--) | يحصل أو يعيّن كلمة المرور لفتح مستند محمي. |
| [setPassword(String value)](#setPassword-java.lang.String-) | يحصل أو يعيّن كلمة المرور لفتح مستند محمي. |
| [getLoadExternalResources()](#getLoadExternalResources--) | يحصل أو يعيّن الخيارات التي تحدد ما إذا كان يجب تحميل موارد المستند الخارجية. |
| [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | يحصل أو يعيّن الخيارات التي تحدد ما إذا كان يجب تحميل موارد المستند الخارجية. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


ينشئ مثيلاً جديداً من فئة LoadOptions.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل أو يعيّن كلمة المرور لفتح مستند محمي. سيتم استخدامها أيضاً لحفظ المستند الموقع كملف محمي.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يحصل أو يعيّن كلمة المرور لفتح مستند محمي. سيتم استخدامها أيضاً لحفظ المستند الموقع كملف محمي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


يحصل أو يعيّن الخيارات التي تحدد ما إذا كان يجب تحميل موارد المستند الخارجية. هذا الخيار عندما يكون معطلاً (false) يسمح بتوفير وقت التحميل للوثائق التي تحتوي على العديد من الروابط الخارجية أو روابط موارد كبيرة. القيمة الافتراضية مفعلة (true).

**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


يحصل أو يعيّن الخيارات التي تحدد ما إذا كان يجب تحميل موارد المستند الخارجية. هذا الخيار عندما يكون معطلاً (false) يسمح بتوفير وقت التحميل للوثائق التي تحتوي على العديد من الروابط الخارجية أو روابط موارد كبيرة. القيمة الافتراضية مفعلة (true).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

