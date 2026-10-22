---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "خيارات الحفظ لمستندات PDF."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

خيارات الحفظ لمستندات PDF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | يُنشئ مثيلاً جديدًا من الفئة PdfSaveOptions بالقيم الافتراضية. |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | يُنشئ مثيلاً جديدًا من الفئة PdfSaveOptions بتنسيق ملف الإخراج المحدد. |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | يُنشئ مثيلاً جديدًا من الفئة PdfSaveOptions بعلم الاستبدال. |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | يُنشئ مثيلاً جديدًا من الفئة PdfSaveOptions بتنسيق ملف الإخراج المحدد وعلامة الاستبدال. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
| [setFileFormat(int value)](#setFileFormat-int-) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


يُنشئ مثيلاً جديدًا من الفئة PdfSaveOptions بالقيم الافتراضية.

### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


يُنشئ مثيلاً جديدًا من الفئة PdfSaveOptions بتنسيق ملف الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileFormat | int | نوع ملف الإخراج [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا من الفئة PdfSaveOptions بعلم الاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| overwriteExistingFile | boolean | علامة لتحديد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا من الفئة PdfSaveOptions بتنسيق ملف الإخراج المحدد وعلامة الاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileFormat | int | نوع ملف الإخراج [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
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
