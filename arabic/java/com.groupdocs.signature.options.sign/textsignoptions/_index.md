---
title: "TextSignOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات توقيع النص."
type: docs
weight: 18
url: /ar/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

يمثل خيارات توقيع النص.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | ينشئ نسخة جديدة من فئة SignTextOptions بالقيم الافتراضية. |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | ينشئ نسخة جديدة من فئة SignTextOptions بالنص. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getLeft()](#getLeft--) | الموضع X الأيسر للتوقيع على صفحة المستند بقيم القياس |
(بكسل، نسب مئوية أو مليمترات راجع خاصية [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | الموضع X الأيسر للتوقيع على صفحة المستند بقيم القياس |
(بكسل، نسب مئوية أو مليمترات راجع خاصية [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getTop()](#getTop--) | الموضع Y العلوي للتوقيع على صفحة المستند بقيم القياس |
(بكسل، نسب مئوية أو مليمترات راجع خاصية [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | الموضع Y العلوي للتوقيع على صفحة المستند بقيم القياس |
(بكسل، نسب مئوية أو مليمترات راجع خاصية [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | عرض التوقيع على صفحة المستند بقيم القياس |
(البكسل، النسب المئوية أو المليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) خاصية SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | عرض التوقيع على صفحة المستند بقيم القياس |
(البكسل، النسب المئوية أو المليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) خاصية SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | ارتفاع التوقيع على صفحة المستند بقيم القياس |
(البكسل، النسب المئوية أو المليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) خاصية SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | ارتفاع التوقيع على صفحة المستند بقيم القياس |
(البكسل، النسب المئوية أو المليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) خاصية SizeMeasureType).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Left و Top. |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Left و Top. |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Width و Height. |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Width و Height. |
|
|  | [getStretch()](#getStretch--) | وضع التمدد على صفحة المستند. |
|
|  | [setStretch(int value)](#setStretch-int-) | وضع التمدد على صفحة المستند. |
|
|  | [getRotationAngle()](#getRotationAngle--) | زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | محاذاة أفقية للتوقيع على صفحة المستند. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | محاذاة أفقية للتوقيع على صفحة المستند. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | محاذاة عمودية للتوقيع على صفحة المستند. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | محاذاة عمودية للتوقيع على صفحة المستند. |
|
|  | [getMargin()](#getMargin--) | يحصل أو يضبط المسافة بين التوقيع وحواف المستند. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | يحصل أو يضبط المسافة بين التوقيع وحواف المستند. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | يحصل أو يضبط نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | يحصل أو يضبط نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش. |
|
|  | [getTransparency()](#getTransparency--) | يحصل أو يضبط شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | يحصل أو يضبط شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). |
|
|  | [getText()](#getText--) | يحصل أو يضبط نص التوقيع. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يحصل أو يضبط نص التوقيع. |
|
|  | [getFont()](#getFont--) | يحصل أو يضبط خط التوقيع. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | يحصل أو يضبط خط التوقيع. |
|
|  | [getForeColor()](#getForeColor--) | يحصل أو يضبط لون المقدمة للتوقيع. |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | يحصل أو يضبط لون المقدمة للتوقيع. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | يحصل أو يضبط نوع تنفيذ توقيع النص. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | يحصل أو يضبط نوع تنفيذ توقيع النص. |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | محاذاة أفقية للنص داخل التوقيع. |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | محاذاة أفقية للنص داخل التوقيع. |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | محاذاة رأسية للنص داخل التوقيع. |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | محاذاة رأسية للنص داخل التوقيع. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | يحصل أو يضبط عنوان حقل النموذج النصي لوضع توقيع النص فيه. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | يحصل أو يضبط عنوان حقل النموذج النصي لوضع توقيع النص فيه. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | يحصل أو يضبط نوع حقل النموذج لوضع توقيع النص فيه. |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | يحصل أو يضبط نوع حقل النموذج لوضع توقيع النص فيه. |
|
|  | [getShapeType()](#getShapeType--) | يحصل أو يضبط نوع الشكل لوضع النص. |
|
|  | [setShapeType(int value)](#setShapeType-int-) | يحصل أو يضبط نوع الشكل لوضع النص. |
|
|  | [getSignatureID()](#getSignatureID--) | يحصل أو يضبط المعرف الفريد للتوقيع. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | يحصل أو يضبط المعرف الفريد للتوقيع. |
|
|  | [getBorder()](#getBorder--) | حدد إعدادات الحدود |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | حدد إعدادات الحدود |
|
|  | [getBackground()](#getBackground--) | يحصل أو يضبط إعدادات خلفية التوقيع. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | يحصل أو يضبط إعدادات خلفية التوقيع. |
|
|  | [getNative()](#getNative--) | يحصل أو يضبط الخاصية الأصلية. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | يحصل أو يضبط الخاصية الأصلية. |
|
|  | [getShapePosition()](#getShapePosition--) | يحدد أين يجب عرض الشكل في تخطيط المستند |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | يحدد أين يجب عرض الشكل في تخطيط المستند |
|
|  | [validate()](#validate--) | طريقة داخلية للتحقق من صحة معلمات الخيارات. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


ينشئ نسخة جديدة من فئة SignTextOptions بالقيم الافتراضية.


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


ينشئ نسخة جديدة من فئة SignTextOptions بالنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص التوقيع. |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


الموضع X الأيسر للتوقيع على صفحة المستند بقيم القياس
(بكسل، نسب مئوية أو مليمترات راجع خاصية [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(يعمل إذا لم يتم تحديد المحاذاة الأفقية).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


الموضع X الأيسر للتوقيع على صفحة المستند بقيم القياس
(بكسل، نسب مئوية أو مليمترات راجع خاصية [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(يعمل إذا لم يتم تحديد المحاذاة الأفقية).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


الموضع Y العلوي للتوقيع على صفحة المستند بقيم القياس
(بكسل، نسب مئوية أو مليمترات راجع خاصية [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(يعمل إذا لم يتم تحديد المحاذاة العمودية).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


الموضع Y العلوي للتوقيع على صفحة المستند بقيم القياس
(بكسل، نسب مئوية أو مليمترات راجع خاصية [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(يعمل إذا لم يتم تحديد المحاذاة العمودية).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


عرض التوقيع على صفحة المستند بقيم القياس
(البكسل، النسب المئوية أو المليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) خاصية SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


عرض التوقيع على صفحة المستند بقيم القياس
(البكسل، النسب المئوية أو المليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) خاصية SizeMeasureType).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ارتفاع التوقيع على صفحة المستند بقيم القياس
(البكسل، النسب المئوية أو المليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) خاصية SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ارتفاع التوقيع على صفحة المستند بقيم القياس
(البكسل، النسب المئوية أو المليمترات انظر [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) خاصية SizeMeasureType).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Left و Top.


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Left و Top.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Width و Height.


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Width و Height.


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


محاذاة عمودية للتوقيع على صفحة المستند.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


محاذاة عمودية للتوقيع على صفحة المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


يحصل أو يضبط المسافة بين التوقيع وحواف المستند.
(يعمل فقط إذا تم تحديد المحاذاة الأفقية أو العمودية).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


يحصل أو يضبط المسافة بين التوقيع وحواف المستند.
(يعمل فقط إذا تم تحديد المحاذاة الأفقية أو العمودية).


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


يحصل أو يعيّن شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). القيمة الافتراضية هي 0 (معتم).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


يحصل أو يعيّن شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). القيمة الافتراضية هي 0 (معتم).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getText() {#getText--}
```
public final String getText()
```


يحصل أو يضبط نص التوقيع.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحصل أو يضبط نص التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


يحصل أو يضبط خط التوقيع.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


يحصل أو يضبط خط التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


يحصل أو يضبط لون المقدمة للتوقيع.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


يحصل أو يضبط لون المقدمة للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


يحصل أو يضبط نوع تنفيذ توقيع النص.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


يحصل أو يضبط نوع تنفيذ توقيع النص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


محاذاة أفقية للنص داخل التوقيع.
هذه الميزة مدعومة فقط لتنفيذات توقيع Image و Annotation.
(انظر [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) خاصية SignatureImplementation).


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


محاذاة أفقية للنص داخل التوقيع.
هذه الميزة مدعومة فقط لتنفيذات توقيع Image و Annotation.
(انظر [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) خاصية SignatureImplementation).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


محاذاة رأسية للنص داخل التوقيع.
هذه الميزة مدعومة فقط لتنفيذ توقيع Image.
(انظر [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) خاصية SignatureImplementation).


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


محاذاة رأسية للنص داخل التوقيع.
هذه الميزة مدعومة فقط لتنفيذ توقيع Image.
(انظر [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) خاصية SignatureImplementation).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


يحصل أو يضبط عنوان حقل النموذج النصي لوضع توقيع النص فيه.
يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


يحصل أو يضبط عنوان حقل النموذج النصي لوضع توقيع النص فيه.
يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


يحصل أو يضبط نوع حقل النموذج لوضع توقيع النص فيه.
يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField.
القيمة الافتراضية هي AllTextTypes.


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


يحصل أو يضبط نوع حقل النموذج لوضع توقيع النص فيه.
يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField.
القيمة الافتراضية هي AllTextTypes.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


يحصل أو يضبط نوع الشكل لوضع النص.
يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextStamp.
القيمة الافتراضية هي Rectangle.


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


يحصل أو يضبط نوع الشكل لوضع النص.
يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextStamp.
القيمة الافتراضية هي Rectangle.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


يحصل أو يضبط المعرف الفريد للتوقيع. يمكن استخدامه في خيارات التحقق من التوقيع. الخاصية مدعومة فقط لمستندات Pdf.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


يحصل أو يضبط المعرف الفريد للتوقيع. يمكن استخدامه في خيارات التحقق من التوقيع. الخاصية مدعومة فقط لمستندات Pdf.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

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

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


يحصل أو يضبط إعدادات خلفية التوقيع.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


يحصل أو يضبط إعدادات خلفية التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


يحصل أو يضبط الخاصية الأصلية. إذا تم ضبطها يمكن استخدام توقيعات خاصة بالمستند.
العلامة المائية النصية الأصلية لمستندات WordProcessing تختلف عن العادية، على سبيل المثال.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


يحصل أو يضبط الخاصية الأصلية. إذا تم ضبطها يمكن استخدام توقيعات خاصة بالمستند.
العلامة المائية النصية الأصلية لمستندات WordProcessing تختلف عن العادية، على سبيل المثال.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


يحدد أين يجب عرض الشكل في تخطيط المستند


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


يحدد أين يجب عرض الشكل في تخطيط المستند


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### validate() {#validate--}
```
public void validate()
```


طريقة داخلية للتحقق من صحة معلمات الخيارات.


### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
