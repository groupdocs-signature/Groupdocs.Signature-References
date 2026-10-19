---
title: "PngSaveOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "خيارات حفظ Png للمستندات الصورة."
type: docs
weight: 22
url: /ar/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

خيارات حفظ Png للمستندات الصورة.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PngSaveOptions()](#PngSaveOptions--) | ينشئ PngSaveOptions بالقيم الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getBitDepth()](#getBitDepth--) | عمق البت. |
|
|  | [setBitDepth(byte value)](#setBitDepth-byte-) | عمق البت. |
|
|  | [getColorType()](#getColorType--) | يحصل أو يعيّن نوع الـ |
PngColorType
.
|
|  | [setColorType(int value)](#setColorType-int-) | يحصل أو يعيّن نوع الـ |
PngColorType
.
|
|  | [getCompressionLevel()](#getCompressionLevel--) | مستوى ضغط صورة png في النطاق من 0 إلى 9، حيث 9 هو أقصى ضغط |
و0 هو وضع التخزين.
|
|  | [setCompressionLevel(int value)](#setCompressionLevel-int-) | مستوى ضغط صورة png في النطاق من 0 إلى 9، حيث 9 هو أقصى ضغط |
و0 هو وضع التخزين.
|
|  | [getFilterType()](#getFilterType--) | يحصل أو يعيّن نوع الفلتر |
PngFilterType
يُستخدم أثناء عملية حفظ ملف png.
|
|  | [setFilterType(int value)](#setFilterType-int-) | يحصل أو يعيّن نوع الفلتر |
PngFilterType
يُستخدم أثناء عملية حفظ ملف png.
|
|  | [getProgressive()](#getProgressive--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا PngSaveOptions تقدميًا. |
|
|  | [setProgressive(boolean value)](#setProgressive-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا PngSaveOptions تقدميًا. |
|
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


ينشئ PngSaveOptions بالقيم الافتراضية.


### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


عمق البت.


**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


عمق البت.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


يحصل أو يعيّن نوع الـ
PngColorType
.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


يحصل أو يعيّن نوع الـ
PngColorType
.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


مستوى ضغط صورة png في النطاق من 0 إلى 9، حيث 9 هو أقصى ضغط
و0 هو وضع التخزين.


**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


مستوى ضغط صورة png في النطاق من 0 إلى 9، حيث 9 هو أقصى ضغط
و0 هو وضع التخزين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


يحصل أو يعيّن نوع الفلتر
PngFilterType
يُستخدم أثناء عملية حفظ ملف png.


**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


يحصل أو يعيّن نوع الفلتر
PngFilterType
يُستخدم أثناء عملية حفظ ملف png.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا PngSaveOptions تقدميًا.


**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا PngSaveOptions تقدميًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

