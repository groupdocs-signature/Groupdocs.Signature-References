---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات توقيع الصورة."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

يمثل خيارات توقيع الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageSignOptions()](#ImageSignOptions--) | ينشئ مثيلاً جديداً من الفئة ImageSignOptions بالقيم الافتراضية. |
| [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة ImageSignOptions بملف الصورة. |
| [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | ينشئ مثيلاً جديداً من الفئة ImageSignOptions بتدفق الصورة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | يحصل أو يعيّن مسار ملف صورة التوقيع. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | يحصل أو يعيّن مسار ملف صورة التوقيع. |
| [getImageStream()](#getImageStream--) | يحصل أو يعيّن تدفق صورة التوقيع. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | يحصل أو يعيّن تدفق صورة التوقيع. |
| [getLeft()](#getLeft--) | الموضع X الأيسر للتوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات، انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setLeft(int value)](#setLeft-int-) | الموضع X الأيسر للتوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات، انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getTop()](#getTop--) | الموضع Y العلوي للتوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات، انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setTop(int value)](#setTop-int-) | الموضع Y العلوي للتوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات، انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getWidth()](#getWidth--) | عرض التوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setWidth(int value)](#setWidth-int-) | عرض التوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [getHeight()](#getHeight--) | ارتفاع التوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات، انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setHeight(int value)](#setHeight-int-) | ارتفاع التوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات، انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [getLocationMeasureType()](#getLocationMeasureType--) | نوع القياس (بكسل أو نسب مئوية أو مليمترات) للخاصيتين Left و Top. |
| [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | نوع القياس (بكسل أو نسب مئوية أو مليمترات) للخاصيتين Left و Top. |
| [getSizeMeasureType()](#getSizeMeasureType--) | نوع القياس (بكسل أو نسب مئوية أو مليمترات) للخاصيتين Width و Height. |
| [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | نوع القياس (بكسل أو نسب مئوية أو مليمترات) للخاصيتين Width و Height. |
| [getStretch()](#getStretch--) | وضع التمدد على صفحة المستند. |
| [setStretch(int value)](#setStretch-int-) | وضع التمدد على صفحة المستند. |
| [getRotationAngle()](#getRotationAngle--) | زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة). |
| [setRotationAngle(int value)](#setRotationAngle-int-) | زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة). |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | محاذاة أفقية للتوقيع على صفحة المستند. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | محاذاة أفقية للتوقيع على صفحة المستند. |
| [getVerticalAlignment()](#getVerticalAlignment--) | محاذاة رأسية للتوقيع على صفحة المستند. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | محاذاة رأسية للتوقيع على صفحة المستند. |
| [getMargin()](#getMargin--) | يحصل أو يضبط المسافة بين التوقيع وحواف المستند. |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | يحصل أو يضبط المسافة بين التوقيع وحواف المستند. |
| [getMarginMeasureType()](#getMarginMeasureType--) | يحصل أو يضبط نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش. |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | يحصل أو يضبط نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش. |
| [getTransparency()](#getTransparency--) | يحصل أو يضبط شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). |
| [setTransparency(double value)](#setTransparency-double-) | يحصل أو يضبط شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). |
| [getShapePosition()](#getShapePosition--) | يحدد مكان عرض الشكل في تخطيط المستند |
| [setShapePosition(int value)](#setShapePosition-int-) | يحدد مكان عرض الشكل في تخطيط المستند |
| [getRectangle()](#getRectangle--) | مستطيل المنطقة لوضع الصورة على المستند. |
| [getBorder()](#getBorder--) | حدد إعدادات الحدود |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | حدد إعدادات الحدود |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
| [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | ينشئ نسخة جديدة من الفئة ImageSignOptions مع صورة معرفة مسبقًا من Base64. |
| [dispose()](#dispose--) | يمسح الموارد الداخلية |
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


ينشئ مثيلاً جديداً من الفئة ImageSignOptions بالقيم الافتراضية.

### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


ينشئ مثيلاً جديداً من الفئة ImageSignOptions بملف الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageFilePath | java.lang.String | مسار ملف الصورة |

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


ينشئ مثيلاً جديداً من الفئة ImageSignOptions بتدفق الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageStream | java.io.InputStream | دفق الصورة |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


يحصل أو يضبط مسار ملف صورة التوقيع. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد ImageStream.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


يحصل أو يضبط مسار ملف صورة التوقيع. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد ImageStream.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


يحصل أو يضبط دفق صورة التوقيع. إذا تم تحديد هذه الخاصية فستُستَخدم دائمًا بدلاً من ImageGuid.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


يحصل أو يضبط دفق صورة التوقيع. إذا تم تحديد هذه الخاصية فستُستَخدم دائمًا بدلاً من ImageGuid.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


الموضع X الأيسر للتوقيع على صفحة المستند بقيم القياس (بكسل، نسب مئوية أو مليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة الأفقية).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


الموضع X الأيسر للتوقيع على صفحة المستند بقيم القياس (بكسل، نسب مئوية أو مليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة الأفقية).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


الموضع Y العلوي للتوقيع على صفحة المستند بقيم القياس (بكسل، نسب مئوية أو مليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة الرأسية).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


الموضع Y العلوي للتوقيع على صفحة المستند بقيم القياس (بكسل، نسب مئوية أو مليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة الرأسية).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


عرض التوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


عرض التوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ارتفاع التوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات، انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ارتفاع التوقيع على صفحة المستند بقيم القياس (بكسل أو نسب مئوية أو مليمترات، انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


نوع القياس (بكسل أو نسب مئوية أو مليمترات) للخاصيتين Left و Top.

**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


نوع القياس (بكسل أو نسب مئوية أو مليمترات) للخاصيتين Left و Top.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


نوع القياس (بكسل أو نسب مئوية أو مليمترات) للخاصيتين Width و Height.

**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


نوع القياس (بكسل أو نسب مئوية أو مليمترات) للخاصيتين Width و Height.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


وضع التمدد على صفحة المستند.

**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


وضع التمدد على صفحة المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة).

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


محاذاة أفقية للتوقيع على صفحة المستند.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


محاذاة أفقية للتوقيع على صفحة المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


محاذاة رأسية للتوقيع على صفحة المستند.

**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


محاذاة رأسية للتوقيع على صفحة المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


يحصل أو يضبط المسافة بين التوقيع وحواف المستند. (يعمل فقط إذا تم تحديد المحاذاة الأفقية أو الرأسية).

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


يحصل أو يضبط المسافة بين التوقيع وحواف المستند. (يعمل فقط إذا تم تحديد المحاذاة الأفقية أو الرأسية).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


يحصل أو يضبط نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش.

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


يحصل أو يضبط نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


يحصل أو يضبط شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). القيمة الافتراضية هي 0 (معتم).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


يحصل أو يضبط شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). القيمة الافتراضية هي 0 (معتم).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


يحدد مكان عرض الشكل في تخطيط المستند

**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


يحدد مكان عرض الشكل في تخطيط المستند

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


مستطيل المنطقة لوضع الصورة على المستند.

**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


حدد إعدادات الحدود

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


حدد إعدادات الحدود

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.

**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


ينشئ نسخة جديدة من الفئة ImageSignOptions مع صورة معرفة مسبقًا من Base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| base64Content | java.lang.String | محتوى الصورة بصيغة سلسلة Base64 |

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


يمسح الموارد الداخلية

