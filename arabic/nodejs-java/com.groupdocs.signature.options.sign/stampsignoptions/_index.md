---
title: "StampSignOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات توقيع الطابع."
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

يمثل خيارات توقيع الطابع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [StampSignOptions()](#StampSignOptions--) | ينشئ مثيلاً جديداً من الفئة StampSignOptions بالقيم الافتراضية. |
| [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | ينشئ مثيلاً جديداً من الفئة StampSignOptions بخيارات المحاذاة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getStampType()](#getStampType--) | يحصل أو يضبط نوع الختم. |
| [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | يحصل أو يضبط نوع الختم. |
| [getOuterLines()](#getOuterLines--) | قائمة الخطوط الخارجية المرسومة كدوائر متحدة المركز. |
| [getInnerLines()](#getInnerLines--) | قائمة الخطوط الداخلية المرسومة كمجموعة من المستطيلات. |
| [getBackground()](#getBackground--) | يحصل أو يضبط خلفية الختم. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | يحصل أو يضبط خلفية الختم. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل أو يضبط لون الخلفية للتوقيع. |
| [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | يحصل أو يضبط لون الخلفية للتوقيع. |
| [getBackgroundBrush()](#getBackgroundBrush--) | الحصول أو تعيين فرشاة خلفية التوقيع. |
| [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | الحصول أو تعيين فرشاة خلفية التوقيع. |
| [getBackgroundColorCropType()](#getBackgroundColorCropType--) | الحصول أو تعيين نوع قص لون الخلفية للتوقيع. |
| [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | الحصول أو تعيين نوع قص لون الخلفية للتوقيع. |
| [getBackgroundImageCropType()](#getBackgroundImageCropType--) | الحصول أو تعيين نوع قص صورة الخلفية للتوقيع. |
| [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | الحصول أو تعيين نوع قص صورة الخلفية للتوقيع. |
| [toString()](#toString--) | تجاوز تحويل السلسلة |
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


ينشئ مثيلاً جديداً من الفئة StampSignOptions بالقيم الافتراضية.

### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


ينشئ مثيلاً جديداً من الفئة StampSignOptions بخيارات المحاذاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| يسار | int | الإحداثي x للحافة العلوية اليسرى لتوقيع الختم |
| أعلى | int | الإحداثي y للحافة العلوية اليسرى لتوقيع الختم |
| العرض | int | عرض توقيع الختم |
| الارتفاع | int | ارتفاع توقيع الختم |

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


الحصول أو تعيين نوع الختم. القيمة الافتراضية هي دائري.

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


الحصول أو تعيين نوع الختم. القيمة الافتراضية هي دائري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


قائمة الخطوط الخارجية المرسومة كدوائر متحدة المركز.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


قائمة الخطوط الداخلية المرسومة كمجموعة من المستطيلات.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


يحصل أو يضبط خلفية الختم.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


يحصل أو يضبط خلفية الختم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


يحصل أو يضبط لون الخلفية للتوقيع.

**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


يحصل أو يضبط لون الخلفية للتوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


الحصول أو تعيين فرشاة خلفية التوقيع. القيمة الافتراضية هي null.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


الحصول أو تعيين فرشاة خلفية التوقيع. القيمة الافتراضية هي null.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


الحصول أو تعيين نوع قص لون الخلفية للتوقيع.

**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


الحصول أو تعيين نوع قص لون الخلفية للتوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


الحصول أو تعيين نوع قص صورة الخلفية للتوقيع.

**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


الحصول أو تعيين نوع قص صورة الخلفية للتوقيع.

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
