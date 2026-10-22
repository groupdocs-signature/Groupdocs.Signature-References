---
title: "SaveOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يسمح بتحديد خيارات إضافية مثل كلمة المرور عند حفظ مستند للتوقيع."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

يسمح بتحديد خيارات إضافية (مثل كلمة المرور) عند حفظ مستند للتوقيع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SaveOptions()](#SaveOptions--) | يُهيئ مثيلاً جديداً من فئة SaveOptions بالقيم الافتراضية. |
| [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | يُهيئ مثيلاً جديداً من فئة SaveOptions بنوع الإخراج المحدد وعلمية الاستبدال. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | يحصل أو يعيّن ما إذا كان سيتم استبدال الملف الموجود بملف الإخراج الجديد. |
| [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | يحصل أو يعيّن ما إذا كان سيتم استبدال الملف الموجود بملف الإخراج الجديد. |
| [getPassword()](#getPassword--) | يحصل أو يحدد كلمة المرور لحفظ المستند الموقّع بحماية كلمة المرور. |
| [setPassword(String value)](#setPassword-java.lang.String-) | يحصل أو يحدد كلمة المرور لحفظ المستند الموقّع بحماية كلمة المرور. |
| [getUseOriginalPassword()](#getUseOriginalPassword--) | يحصل أو يحدد ما إذا كان سيتم استخدام كلمة المرور من LoadOptions لحفظ المستند الموقّع كحماية. |
| [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | يحصل أو يحدد ما إذا كان سيتم استخدام كلمة المرور من LoadOptions لحفظ المستند الموقّع كحماية. |
| [getAddMissingExtenstion()](#getAddMissingExtenstion--) | يحصل أو يحدد العلامة لإضافة الامتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي false. |
| [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | يحصل أو يحدد العلامة لإضافة الامتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي false. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


يُهيئ مثيلاً جديداً من فئة SaveOptions بالقيم الافتراضية.

### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


يُهيئ مثيلاً جديداً من فئة SaveOptions بنوع الإخراج المحدد وعلمية الاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| overwriteExistingFile | boolean | علامة لتحديد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


يحصل أو يحدد ما إذا كان سيتم استبدال الملف الموجود بملف إخراج جديد. وإلا سيتم إنشاء ملف جديد مع رقم كلاحقة.

**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


يحصل أو يحدد ما إذا كان سيتم استبدال الملف الموجود بملف إخراج جديد. وإلا سيتم إنشاء ملف جديد مع رقم كلاحقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل أو يحدد كلمة المرور لحفظ المستند الموقّع بحماية كلمة المرور. هذه الخاصية غير مدعومة للمستندات من نوع Image.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يحصل أو يحدد كلمة المرور لحفظ المستند الموقّع بحماية كلمة المرور. هذه الخاصية غير مدعومة للمستندات من نوع Image.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


يحصل أو يحدد ما إذا كان سيتم استخدام كلمة المرور من LoadOptions لحفظ المستند الموقّع كحماية. القيمة الافتراضية هي true. هذه الخاصية غير مدعومة للمستندات من نوع Image.

**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


يحصل أو يحدد ما إذا كان سيتم استخدام كلمة المرور من LoadOptions لحفظ المستند الموقّع كحماية. القيمة الافتراضية هي true. هذه الخاصية غير مدعومة للمستندات من نوع Image.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


يحصل أو يحدد العلامة لإضافة الامتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي false.

**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


يحصل أو يحدد العلامة لإضافة الامتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

