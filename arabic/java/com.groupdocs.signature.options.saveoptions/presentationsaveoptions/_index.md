---
title: "PresentationSaveOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "خيارات الحفظ لمستندات العروض التقديمية."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

خيارات الحفظ لمستندات العروض التقديمية.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | إنشاء مثيل جديد من فئة PresentationSaveOptions بالقيم الافتراضية. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | إنشاء مثيل جديد من فئة PresentationSaveOptions بالتنسيق المحدد لملف الإخراج. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | إنشاء مثيل جديد من فئة PresentationSaveOptions بالنوع المحدد للملف وعلامة تجاوز الكتابة. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | يُنشئ مثيلاً جديدًا لفئة PresentationSaveOptions مع تنسيق ملف الإخراج المحدد وعلامة الاستبدال. |
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
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


إنشاء مثيل جديد من فئة PresentationSaveOptions بالقيم الافتراضية.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


إنشاء مثيل جديد من فئة PresentationSaveOptions بالتنسيق المحدد لملف الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | int | نوع ملف الإخراج [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


إنشاء مثيل جديد من فئة PresentationSaveOptions بالنوع المحدد للملف وعلامة تجاوز الكتابة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | علم يحدد ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


يُنشئ مثيلاً جديدًا لفئة PresentationSaveOptions مع تنسيق ملف الإخراج المحدد وعلامة الاستبدال.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | int | نوع ملف الإخراج [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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
