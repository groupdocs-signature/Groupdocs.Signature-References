---
title: "GifSaveOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "خيارات حفظ تنسيق Gif للمستندات الصورة."
type: docs
weight: 15
url: /ar/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

خيارات حفظ تنسيق Gif للمستندات الصورة.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [GifSaveOptions()](#GifSaveOptions--) | ينشئ GifSaveOptions بالقيم الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | يحصل أو يعيّن فهرس لون خلفية GIF. |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | يحصل أو يعيّن فهرس لون خلفية GIF. |
|
|  | [getColorResolution()](#getColorResolution--) | يحصل أو يعيّن دقة ألوان GIF. |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | يحصل أو يعيّن دقة ألوان GIF. |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | يحصل أو يعيّن قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة. |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة. |
|
|  | [hasTrailer()](#hasTrailer--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على ذيل. |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على ذيل. |
|
|  | [getInterlaced()](#getInterlaced--) | صحيح إذا كان يجب تشابك الصورة. |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | صحيح إذا كان يجب تشابك الصورة. |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت إدخالات لوحة الألوان مرتبة. |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت إدخالات لوحة الألوان مرتبة. |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | يحصل أو يعيّن نسبة أبعاد بكسل GIF. |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | يحصل أو يعيّن نسبة أبعاد بكسل GIF. |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


ينشئ GifSaveOptions بالقيم الافتراضية.


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


يحصل أو يعيّن فهرس لون خلفية GIF.


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


يحصل أو يعيّن فهرس لون خلفية GIF.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


يحصل أو يعيّن دقة ألوان GIF.

<br />

*** ** * ** ***

دقة اللون - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم لوحة الألوان الكاملة التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل هي 3، فإن لوحة ألوان الصورة الأصلية كانت تحتوي على 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة للإشارة إلى غنى لوحة الألوان الأصلية، حتى إذا لم يكن كل لون من اللوحة الكاملة متاحًا على الجهاز المصدر.

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


يحصل أو يعيّن دقة ألوان GIF.

<br />

*** ** * ** ***

دقة اللون - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم لوحة الألوان الكاملة التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل هي 3، فإن لوحة ألوان الصورة الأصلية كانت تحتوي على 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة للإشارة إلى غنى لوحة الألوان الأصلية، حتى إذا لم يكن كل لون من اللوحة الكاملة متاحًا على الجهاز المصدر.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة.

<br />

*** ** * ** ***

تصحيح لوحة الألوان يعني أنه كلما تم تصدير الصورة إلى GIF، سيتم تحليل ألوان الصورة المصدر لبناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت، ومع ذلك ستحصل الصورة الناتجة على أفضل لوحة ألوان مطابقة وتكون النتيجة بصريًا أفضل.

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة.

<br />

*** ** * ** ***

تصحيح لوحة الألوان يعني أنه كلما تم تصدير الصورة إلى GIF، سيتم تحليل ألوان الصورة المصدر لبناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت، ومع ذلك ستحصل الصورة الناتجة على أفضل لوحة ألوان مطابقة وتكون النتيجة بصريًا أفضل.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على ذيل.


**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على ذيل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


صحيح إذا كان يجب تشابك الصورة.


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


صحيح إذا كان يجب تشابك الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت إدخالات لوحة الألوان مرتبة.


**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت إدخالات لوحة الألوان مرتبة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


يحصل أو يعيّن نسبة أبعاد بكسل GIF.

<br />

*** ** * ** ***

نسبة أبعاد البكسل - العامل المستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: النسبة = (نسبة أبعاد البكسل + 15) / 64. تُعرّف نسبة أبعاد البكسل بأنها ناتج قسمة عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


يحصل أو يعيّن نسبة أبعاد بكسل GIF.

<br />

*** ** * ** ***

نسبة أبعاد البكسل - العامل المستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: النسبة = (نسبة أبعاد البكسل + 15) / 64. تُعرّف نسبة أبعاد البكسل بأنها ناتج قسمة عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte |  |

