---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "خيارات حفظ تنسيق GIF للمستندات الصورة."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

خيارات حفظ تنسيق GIF للمستندات الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifSaveOptions()](#GifSaveOptions--) | ينشئ GifSaveOptions بالقيم الافتراضية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | يحصل أو يضبط فهرس لون خلفية GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | يحصل أو يضبط فهرس لون خلفية GIF. |
| [getColorResolution()](#getColorResolution--) | يحصل أو يضبط دقة ألوان GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | يحصل أو يضبط دقة ألوان GIF. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | يحصل أو يضبط قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة. |
| [hasTrailer()](#hasTrailer--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي. |
| [getInterlaced()](#getInterlaced--) | صحيح إذا كان يجب أن تكون الصورة متشابكة. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | صحيح إذا كان يجب أن تكون الصورة متشابكة. |
| [isPaletteSorted()](#isPaletteSorted--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت مدخلات اللوحة مرتبة. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت مدخلات اللوحة مرتبة. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | يحصل أو يضبط نسبة أبعاد بكسل GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | يحصل أو يضبط نسبة أبعاد بكسل GIF. |
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


ينشئ GifSaveOptions بالقيم الافتراضية.

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


يحصل أو يضبط فهرس لون خلفية GIF.

**Returns:**
بايت
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


يحصل أو يضبط فهرس لون خلفية GIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | بايت |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


يحصل أو يضبط دقة ألوان GIF.

--------------------

دقة اللون - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم اللوحة الكاملة التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل هي 3، فإن لوحة الصورة الأصلية كان لديها 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة للإشارة إلى غنى اللوحة الأصلية، حتى إذا لم يكن كل لون من اللوحة الكاملة متاحًا على الجهاز المصدر.

**Returns:**
بايت
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


يحصل أو يضبط دقة ألوان GIF.

--------------------

دقة اللون - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم اللوحة الكاملة التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل هي 3، فإن لوحة الصورة الأصلية كان لديها 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة للإشارة إلى غنى اللوحة الأصلية، حتى إذا لم يكن كل لون من اللوحة الكاملة متاحًا على الجهاز المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | بايت |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


يحصل أو يضبط قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة.

--------------------

يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF، سيتم تحليل ألوان الصورة المصدر لبناء لوحة ألوان مطابقة بأفضل شكل (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت، ومع ذلك ستحصل الصورة الناتجة على أفضل لوحة ألوان مطابقة وتكون النتيجة أفضل بصريًا.

**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة.

--------------------

يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF، سيتم تحليل ألوان الصورة المصدر لبناء لوحة ألوان مطابقة بأفضل شكل (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت، ومع ذلك ستحصل الصورة الناتجة على أفضل لوحة ألوان مطابقة وتكون النتيجة أفضل بصريًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي.

**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


صحيح إذا كان يجب أن تكون الصورة متشابكة.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


صحيح إذا كان يجب أن تكون الصورة متشابكة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت مدخلات اللوحة مرتبة.

**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت مدخلات اللوحة مرتبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


يحصل أو يضبط نسبة أبعاد بكسل GIF.

--------------------

نسبة أبعاد البكسل - العامل المستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: النسبة = (نسبة أبعاد البكسل + 15) / 64. تُعرّف نسبة أبعاد البكسل بأنها ناتج قسمة عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أعلى بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

**Returns:**
بايت
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


يحصل أو يضبط نسبة أبعاد بكسل GIF.

--------------------

نسبة أبعاد البكسل - العامل المستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: النسبة = (نسبة أبعاد البكسل + 15) / 64. تُعرّف نسبة أبعاد البكسل بأنها ناتج قسمة عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أعلى بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | بايت |  |

