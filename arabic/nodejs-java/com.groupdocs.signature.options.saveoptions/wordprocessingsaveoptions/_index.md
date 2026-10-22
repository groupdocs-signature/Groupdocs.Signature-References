---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "خيارات الحفظ لمستندات معالجة النصوص."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

خيارات الحفظ لمستندات معالجة النصوص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | يُنشئ مثيلاً جديدًا من الفئة WordProcessingSaveOptions بالقيم الافتراضية. |
| [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | يُنشئ مثيلاً جديدًا من الفئة WordProcessingSaveOptions بتنسيق ملف الإخراج المحدد. |
| [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | يُنشئ مثيلاً جديدًا من الفئة WordProcessingSaveOptions بنوع الإخراج المحدد وعلامة الاستبدال. |
| [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | يُنشئ مثيلاً جديدًا من الفئة WordProcessingSaveOptions بتنسيق ملف الإخراج المحدد وعلامة الاستبدال. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
| [setFileFormat(int value)](#setFileFormat-int-) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
| [toString()](#toString--) | تجاوز تحويل السلسلة |
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


يُنشئ مثيلاً جديدًا من الفئة WordProcessingSaveOptions بالقيم الافتراضية.

### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


يُنشئ مثيلاً جديدًا من الفئة WordProcessingSaveOptions بتنسيق ملف الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileFormat | int | نوع ملف الإخراج [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا من الفئة WordProcessingSaveOptions بنوع الإخراج المحدد وعلامة الاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| overwriteExistingFile | boolean | علامة لتحديد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا من الفئة WordProcessingSaveOptions بتنسيق ملف الإخراج المحدد وعلامة الاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileFormat | int | نوع ملف الإخراج [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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


تجاوز تحويل السلسلة

**Returns:**
java.lang.String -
