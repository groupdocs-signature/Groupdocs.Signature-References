---
title: "WordProcessingSaveOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "خيارات الحفظ لمستندات معالجة النصوص."
type: docs
weight: 15
url: /ar/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

خيارات الحفظ لمستندات معالجة النصوص.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | يُنشئ مثيلاً جديدًا لفئة WordProcessingSaveOptions بالقيم الافتراضية. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | يُنشئ مثيلاً جديدًا لفئة WordProcessingSaveOptions مع تنسيق ملف الإخراج المحدد. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | يُنشئ مثيلاً جديدًا لفئة WordProcessingSaveOptions مع نوع الإخراج المحدد وعلامة الاستبدال. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | يُنشئ مثيلاً جديدًا لفئة WordProcessingSaveOptions مع تنسيق ملف الإخراج المحدد وعلامة الاستبدال. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | الحصول على أو تعيين تنسيق ملف المستند الموقّع. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | الحصول على أو تعيين تنسيق ملف المستند الموقّع. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


يُنشئ مثيلاً جديدًا لفئة WordProcessingSaveOptions بالقيم الافتراضية.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


يُنشئ مثيلاً جديدًا لفئة WordProcessingSaveOptions مع تنسيق ملف الإخراج المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | int | نوع ملف الإخراج [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا لفئة WordProcessingSaveOptions مع نوع الإخراج المحدد وعلامة الاستبدال.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | علم يحدد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا لفئة WordProcessingSaveOptions مع تنسيق ملف الإخراج المحدد وعلامة الاستبدال.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | int | نوع ملف الإخراج [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة


**Returns:**
java.lang.String -
