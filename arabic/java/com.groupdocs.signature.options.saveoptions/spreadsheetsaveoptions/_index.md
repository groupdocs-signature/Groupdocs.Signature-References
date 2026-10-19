---
title: "SpreadsheetSaveOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "خيارات الحفظ لمستندات جداول البيانات."
type: docs
weight: 14
url: /ar/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

خيارات الحفظ لمستندات جداول البيانات.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | يُنشئ مثيلاً جديدًا لفئة SpreadsheetSaveOptions بالقيم الافتراضية. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | يُنشئ مثيلاً جديدًا لفئة SpreadsheetSaveOptions مع تنسيق ملف الإخراج المحدد مسبقًا. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | يُنشئ مثيلاً جديدًا لفئة SpreadsheetSaveOptions مع نوع الإخراج المحدد وعلامة الاستبدال. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | الحصول على أو تعيين تنسيق ملف المستند الموقّع. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | الحصول على أو تعيين تنسيق ملف المستند الموقّع. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


يُنشئ مثيلاً جديدًا لفئة SpreadsheetSaveOptions بالقيم الافتراضية.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


يُنشئ مثيلاً جديدًا لفئة SpreadsheetSaveOptions مع تنسيق ملف الإخراج المحدد مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | int | يحدد تنسيق ملف الإخراج. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا لفئة SpreadsheetSaveOptions مع نوع الإخراج المحدد وعلامة الاستبدال.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | int | يحدد تنسيق ملف الإخراج. |
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


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
