---
title: "BmpSaveOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "خيارات حفظ Bmp للمستندات الصورة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bmpsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class BmpSaveOptions extends ImageSaveOptions
```

خيارات حفظ Bmp للمستندات الصورة.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [BmpSaveOptions()](#BmpSaveOptions--) | ينشئ BmpSaveOptions بالقيم الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getBitsPerPixel()](#getBitsPerPixel--) | يحصل أو يعيّن عدد بتات الصورة لكل بكسل. |
|
|  | [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | يحصل أو يعيّن عدد بتات الصورة لكل بكسل. |
|
|  | [getCompression()](#getCompression--) | يحصل أو يعيّن الضغط. |
|
|  | [setCompression(int value)](#setCompression-int-) | يحصل أو يعيّن الضغط. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | يحصل أو يعيّن الدقة الأفقية. |
|
|  | [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | يحصل أو يعيّن الدقة الأفقية. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | يحصل أو يعيّن الدقة العمودية. |
|
|  | [setVerticalResolution(double value)](#setVerticalResolution-double-) | يحصل أو يعيّن الدقة العمودية. |
|
### BmpSaveOptions() {#BmpSaveOptions--}
```
public BmpSaveOptions()
```


ينشئ BmpSaveOptions بالقيم الافتراضية.


### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


يحصل أو يعيّن عدد بتات الصورة لكل بكسل.


**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


يحصل أو يعيّن عدد بتات الصورة لكل بكسل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


يحصل أو يعيّن الضغط. راجع [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression).


**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


يحصل أو يعيّن الضغط. راجع [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final double getHorizontalResolution()
```


يحصل أو يعيّن الدقة الأفقية. ملاحظة: بسبب التقريب النتيجة
قد يختلف الدقة قليلاً عن القيمة المُمرَّرة.


**Returns:**
double
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public final void setHorizontalResolution(double value)
```


يحصل أو يعيّن الدقة الأفقية. ملاحظة: بسبب التقريب النتيجة
قد يختلف الدقة قليلاً عن القيمة المُمرَّرة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final double getVerticalResolution()
```


يحصل أو يعيّن الدقة العمودية. ملاحظة: بسبب التقريب قد تكون النتيجة
قد يختلف الدقة قليلاً عن القيمة المُمرَّرة.


**Returns:**
double
### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public final void setVerticalResolution(double value)
```


يحصل أو يعيّن الدقة العمودية. ملاحظة: بسبب التقريب قد تكون النتيجة
قد يختلف الدقة قليلاً عن القيمة المُمرَّرة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

