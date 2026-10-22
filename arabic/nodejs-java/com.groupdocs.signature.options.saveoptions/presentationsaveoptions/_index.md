---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "خيارات الحفظ لمستندات العرض."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

خيارات الحفظ لمستندات العرض.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PresentationSaveOptions()](#PresentationSaveOptions--) | يُنشئ مثيلاً جديدًا من الفئة PresentationSaveOptions بالقيم الافتراضية. |
| [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | يُنشئ مثيلاً جديدًا من الفئة PresentationSaveOptions بتنسيق ملف الإخراج المحدد. |
| [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | يُنشئ مثيلاً جديدًا من الفئة PresentationSaveOptions بنوع الإخراج المحدد وعلامة الاستبدال. |
| [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | يُنشئ مثيلاً جديدًا من الفئة PresentationSaveOptions بتنسيق ملف الإخراج المحدد وعلامة الاستبدال. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
| [setFileFormat(int value)](#setFileFormat-int-) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


يُنشئ مثيلاً جديدًا من الفئة PresentationSaveOptions بالقيم الافتراضية.

### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


يُنشئ مثيلاً جديدًا من الفئة PresentationSaveOptions بتنسيق ملف الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileFormat | int | نوع ملف الإخراج [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا من الفئة PresentationSaveOptions بنوع الإخراج المحدد وعلامة الاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| overwriteExistingFile | boolean | علامة لتحديد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا من الفئة PresentationSaveOptions بتنسيق ملف الإخراج المحدد وعلامة الاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileFormat | int | نوع ملف الإخراج [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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
