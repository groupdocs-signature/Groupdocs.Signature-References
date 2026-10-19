---
title: "SaveOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يسمح بتحديد خيارات إضافية مثل كلمة المرور عند حفظ مستند للتوقيع."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

يسمح بتحديد خيارات إضافية (مثل كلمة المرور) عند حفظ مستند للتوقيع.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | ينشئ مثيلاً جديدًا لفئة SaveOptions بالقيم الافتراضية. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | ينشئ مثيلاً جديدًا لفئة SaveOptions بنوع الإخراج المحدد وعلمية الاستبدال. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | يحصل أو يضبط ما إذا كان سيتم استبدال الملف الموجود بملف إخراج جديد. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | يحصل أو يضبط ما إذا كان سيتم استبدال الملف الموجود بملف إخراج جديد. |
|
|  | [getPassword()](#getPassword--) | يحصل أو يضبط كلمة المرور لحفظ المستند الموقّع بحماية كلمة مرور. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يحصل أو يضبط كلمة المرور لحفظ المستند الموقّع بحماية كلمة مرور. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | يحصل أو يضبط ما إذا كان سيتم استخدام كلمة المرور من LoadOptions لحفظ المستند الموقّع كحماية. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | يحصل أو يضبط ما إذا كان سيتم استخدام كلمة المرور من LoadOptions لحفظ المستند الموقّع كحماية. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | يحصل أو يضبط علمًا لإضافة الامتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. |
القيمة الافتراضية هي false.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | يحصل أو يضبط علمًا لإضافة الامتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. |
القيمة الافتراضية هي false.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


ينشئ مثيلاً جديدًا لفئة SaveOptions بالقيم الافتراضية.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


ينشئ مثيلاً جديدًا لفئة SaveOptions بنوع الإخراج المحدد وعلمية الاستبدال.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | علم يحدد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


يحصل أو يضبط ما إذا كان سيتم استبدال الملف الموجود بملف إخراج جديد.
إلا سيتم إنشاء ملف جديد مع رقم كلاحقة.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


يحصل أو يضبط ما إذا كان سيتم استبدال الملف الموجود بملف إخراج جديد.
إلا سيتم إنشاء ملف جديد مع رقم كلاحقة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل أو يضبط كلمة المرور لحفظ المستند الموقّع بحماية كلمة مرور.
هذه الخاصية غير مدعومة للمستندات من نوع Image.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يحصل أو يضبط كلمة المرور لحفظ المستند الموقّع بحماية كلمة مرور.
هذه الخاصية غير مدعومة للمستندات من نوع Image.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


يحصل أو يضبط ما إذا كان سيتم استخدام كلمة المرور من LoadOptions لحفظ المستند الموقّع كحماية.
القيمة الافتراضية هي true.
هذه الخاصية غير مدعومة للمستندات من نوع Image.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


يحصل أو يضبط ما إذا كان سيتم استخدام كلمة المرور من LoadOptions لحفظ المستند الموقّع كحماية.
القيمة الافتراضية هي true.
هذه الخاصية غير مدعومة للمستندات من نوع Image.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


يحصل أو يضبط علمًا لإضافة الامتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج.
القيمة الافتراضية هي false.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


يحصل أو يضبط علمًا لإضافة الامتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج.
القيمة الافتراضية هي false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

