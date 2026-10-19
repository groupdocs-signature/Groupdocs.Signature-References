---
title: "StampSignOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات توقيع الختم."
type: docs
weight: 17
url: /ar/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

يمثل خيارات توقيع الختم.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | يقوم بتهيئة نسخة جديدة من الفئة StampSignOptions بالقيم الافتراضية. |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | يقوم بتهيئة نسخة جديدة من الفئة StampSignOptions بخيارات المحاذاة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getStampType()](#getStampType--) | يحصل أو يضبط نوع الطابع. |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | يحصل أو يضبط نوع الطابع. |
|
|  | [getOuterLines()](#getOuterLines--) | قائمة الخطوط الخارجية المعروضة كدوائر متحدة المركز. |
|
|  | [getInnerLines()](#getInnerLines--) | قائمة الخطوط الداخلية المعروضة كمجموعة من المستطيلات. |
|
|  | [getBackground()](#getBackground--) | يحصل أو يضبط خلفية الطابع. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | يحصل أو يضبط خلفية الطابع. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | الحصول أو الضبط للون الخلفية للتوقيع. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | الحصول أو الضبط للون الخلفية للتوقيع. |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | يحصل أو يضبط فرشاة خلفية التوقيع. |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | يحصل أو يضبط فرشاة خلفية التوقيع. |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | يحصل أو يضبط نوع قص لون الخلفية للتوقيع. |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | يحصل أو يضبط نوع قص لون الخلفية للتوقيع. |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | يحصل أو يضبط نوع قص صورة الخلفية للتوقيع. |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | يحصل أو يضبط نوع قص صورة الخلفية للتوقيع. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


يقوم بتهيئة نسخة جديدة من الفئة StampSignOptions بالقيم الافتراضية.


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


يقوم بتهيئة نسخة جديدة من الفئة StampSignOptions بخيارات المحاذاة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | يسار | int | إحداثي x للحد الأعلى الأيسر لتوقيع الطابع |
|
|  | أعلى | int | إحداثي y للحد الأعلى الأيسر لتوقيع الطابع |
|
|  | العرض | int | عرض توقيع الطابع |
|
|  | الارتفاع | int | ارتفاع توقيع الطابع |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


يحصل أو يضبط نوع الطابع.
القيمة الافتراضية هي Round.


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


يحصل أو يضبط نوع الطابع.
القيمة الافتراضية هي Round.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


قائمة الخطوط الخارجية المعروضة كدوائر متحدة المركز.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


قائمة الخطوط الداخلية المعروضة كمجموعة من المستطيلات.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


يحصل أو يضبط خلفية الطابع.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


يحصل أو يضبط خلفية الطابع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


الحصول أو الضبط للون الخلفية للتوقيع.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


الحصول أو الضبط للون الخلفية للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


يحصل أو يضبط فرشاة خلفية التوقيع. القيمة الافتراضية هي null.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


يحصل أو يضبط فرشاة خلفية التوقيع. القيمة الافتراضية هي null.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


يحصل أو يضبط نوع قص لون الخلفية للتوقيع.


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


يحصل أو يضبط نوع قص لون الخلفية للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


يحصل أو يضبط نوع قص صورة الخلفية للتوقيع.


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


يحصل أو يضبط نوع قص صورة الخلفية للتوقيع.


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
