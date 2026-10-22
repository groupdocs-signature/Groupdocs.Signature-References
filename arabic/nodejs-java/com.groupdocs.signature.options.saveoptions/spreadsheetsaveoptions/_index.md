---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "خيارات الحفظ لمستندات جداول البيانات."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

خيارات الحفظ لمستندات جداول البيانات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | يُنشئ مثيلاً جديدًا من الفئة SpreadsheetSaveOptions بالقيم الافتراضية. |
| [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | يُنشئ مثيلاً جديدًا من الفئة SpreadsheetSaveOptions بتنسيق ملف الإخراج المحدد مسبقًا. |
| [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | يُنشئ مثيلاً جديدًا من الفئة SpreadsheetSaveOptions بنوع الإخراج المحدد وعلامة الاستبدال. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
| [setFileFormat(int value)](#setFileFormat-int-) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


يُنشئ مثيلاً جديدًا من الفئة SpreadsheetSaveOptions بالقيم الافتراضية.

### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


يُنشئ مثيلاً جديدًا من الفئة SpreadsheetSaveOptions بتنسيق ملف الإخراج المحدد مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileFormat | int | يحدد تنسيق ملف الإخراج. |

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا من الفئة SpreadsheetSaveOptions بنوع الإخراج المحدد وعلامة الاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileFormat | int | يحدد تنسيق ملف الإخراج. |
| overwriteExistingFile | boolean | علامة لتحديد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


يحصل أو يضبط تنسيق ملف المستند الموقّع.

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


يحصل أو يضبط تنسيق ملف المستند الموقّع.

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
