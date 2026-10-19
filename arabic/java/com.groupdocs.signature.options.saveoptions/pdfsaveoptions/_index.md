---
title: "PdfSaveOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "خيارات الحفظ لمستندات PDF."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

خيارات الحفظ لمستندات PDF.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | إنشاء مثيل جديد من فئة PdfSaveOptions بالقيم الافتراضية. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | إنشاء مثيل جديد من فئة PdfSaveOptions بالتنسيق المحدد لملف الإخراج. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | إنشاء مثيل جديد من فئة PdfSaveOptions بعلامة تجاوز الكتابة. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | إنشاء مثيل جديد من فئة PdfSaveOptions بالتنسيق المحدد لملف الإخراج وعلامة تجاوز الكتابة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | الحصول على أو تعيين تنسيق ملف المستند الموقّع. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | الحصول على أو تعيين تنسيق ملف المستند الموقّع. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | كلمة مرور الأذونات (كلمة المرور الأساسية) تتطلب كلمة مرور لتغيير إعدادات الأذونات. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | كلمة مرور الأذونات (كلمة المرور الأساسية) تتطلب كلمة مرور لتغيير إعدادات الأذونات. |
|
|  | [getPermissions()](#getPermissions--) | أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


إنشاء مثيل جديد من فئة PdfSaveOptions بالقيم الافتراضية.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


إنشاء مثيل جديد من فئة PdfSaveOptions بالتنسيق المحدد لملف الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | int | نوع ملف الإخراج [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


إنشاء مثيل جديد من فئة PdfSaveOptions بعلامة تجاوز الكتابة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | علم يحدد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


إنشاء مثيل جديد من فئة PdfSaveOptions بالتنسيق المحدد لملف الإخراج وعلامة تجاوز الكتابة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | int | نوع ملف الإخراج [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|
|  | overwriteExistingFile | boolean | علم يحدد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


الحصول على أو تعيين تنسيق ملف المستند الموقّع.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


الحصول على أو تعيين تنسيق ملف المستند الموقّع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


كلمة مرور الأذونات (كلمة المرور الأساسية) تتطلب كلمة مرور لتغيير إعدادات الأذونات.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


كلمة مرور الأذونات (كلمة المرور الأساسية) تتطلب كلمة مرور لتغيير إعدادات الأذونات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات.


لتعديل هذه الأذونات، الـ
PermissionsPassword
يجب تعيينه.
القيمة هي تركيبة من العلامات من [Permissions](../../com.groupdocs.signature.options/permissions).
قيمة
null
تعني عدم تطبيق أذونات صريحة.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
