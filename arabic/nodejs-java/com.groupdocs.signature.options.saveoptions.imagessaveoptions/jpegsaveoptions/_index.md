---
title: "JpegSaveOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "خيارات حفظ JPEG للمستندات الصورة."
type: docs
weight: 19
url: /ar/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

خيارات حفظ JPEG للمستندات الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [JpegSaveOptions()](#JpegSaveOptions--) | ينشئ JpegSaveOptions بالقيم الافتراضية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBitsPerChannel()](#getBitsPerChannel--) | يحصل أو يضبط عدد البتات لكل قناة في صورة jpeg غير مضغوطة. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | يحصل أو يضبط عدد البتات لكل قناة في صورة jpeg غير مضغوطة. |
| [getColorType()](#getColorType--) | يحصل أو يضبط نوع اللون لصورة jpeg. |
| [setColorType(int value)](#setColorType-int-) | يحصل أو يضبط نوع اللون لصورة jpeg. |
| [getComment()](#getComment--) | يحصل أو يضبط تعليق ملف jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | يحصل أو يضبط تعليق ملف jpeg. |
| [getCompressionType()](#getCompressionType--) | يحصل أو يضبط نوع الضغط. |
| [setCompressionType(int value)](#setCompressionType-int-) | يحصل أو يضبط نوع الضغط. |
| [getQuality()](#getQuality--) | يحصل أو يضبط جودة الصورة. |
| [setQuality(int value)](#setQuality-int-) | يحصل أو يضبط جودة الصورة. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | يحصل أو يضبط وضع تقريب العينة لتلائم قيمة 8-بت إلى قيمة n-بت JpegOptions.BitsPerChannel. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | يحصل أو يضبط وضع تقريب العينة لتلائم قيمة 8-بت إلى قيمة n-بت JpegOptions.BitsPerChannel. |
| [getFileFormat()](#getFileFormat--) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
| [setFileFormat(int value)](#setFileFormat-int-) | يحصل أو يضبط تنسيق ملف المستند الموقّع. |
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


ينشئ JpegSaveOptions بالقيم الافتراضية.

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


يحصل أو يضبط عدد البتات لكل قناة في صورة jpeg غير مضغوطة. الآن ندعم من 2 إلى 8 بتات لكل قناة.

**Returns:**
بايت
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


يحصل أو يضبط عدد البتات لكل قناة في صورة jpeg غير مضغوطة. الآن ندعم من 2 إلى 8 بتات لكل قناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | بايت |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


يحصل أو يضبط نوع اللون لصورة jpeg.

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


يحصل أو يضبط نوع اللون لصورة jpeg.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


يحصل أو يضبط تعليق ملف jpeg.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


يحصل أو يضبط تعليق ملف jpeg.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


يحصل أو يضبط نوع الضغط.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


يحصل أو يضبط نوع الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


يحصل أو يضبط جودة الصورة.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


يحصل أو يضبط جودة الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


يحصل أو يضبط وضع تقريب العينة لتلائم قيمة 8-بت إلى قيمة n-بت JpegOptions.BitsPerChannel.

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


يحصل أو يضبط وضع تقريب العينة لتلائم قيمة 8-بت إلى قيمة n-بت JpegOptions.BitsPerChannel.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


يحصل أو يضبط تنسيق ملف المستند الموقع. مخفي لأنه غير مستخدم في فئة الخيارات هذه.

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


يحصل أو يضبط تنسيق ملف المستند الموقع. مخفي لأنه غير مستخدم في فئة الخيارات هذه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

