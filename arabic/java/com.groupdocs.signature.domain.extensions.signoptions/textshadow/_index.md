---
title: "TextShadow"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خصائص ظل النص لتوقيعات النص."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

يمثل خصائص ظل النص لتوقيعات النص.
قد تختلف النتيجة اعتماداً على نوع التوقيع وصيغة المستند.
يوصى باستخدام TextShadow مع توقيع TextAsImage لجميع أنواع المستندات المدعومة،
أيضًا مع TextSignature بسيط و TextSignature كعلامة مائية لـ Cells (.xslx) و Slides (.pptx).
TextSignature بسيط لـ Words (.docx) يُنصح به أيضًا، لكنه يملك وظائف محدودة.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | ينشئ TextShadow بخيارات افتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getDistance()](#getDistance--) | يحصل أو يعيّن المسافة من النص إلى الظل. |
|
|  | [setDistance(double value)](#setDistance-double-) | يحصل أو يعيّن المسافة من النص إلى الظل. |
|
|  | [getAngle()](#getAngle--) | يحصل أو يعيّن الزاوية لوضع الظل بالنسبة للنص. |
|
|  | [setAngle(double value)](#setAngle-double-) | يحصل أو يعيّن الزاوية لوضع الظل بالنسبة للنص. |
|
|  | [getColor()](#getColor--) | يحصل أو يعيّن لون الظل. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | يحصل أو يعيّن لون الظل. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | يحصل أو يعيّن لون الظل. |
|
|  | [getTransparency()](#getTransparency--) | يحصل أو يعيّن شفافية الظل. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | يحصل أو يعيّن شفافية الظل. |
|
|  | [getBlur()](#getBlur--) | يحصل أو يعيّن تمويه الظل. |
|
|  | [setBlur(double value)](#setBlur-double-) | يحصل أو يعيّن تمويه الظل. |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


ينشئ TextShadow بخيارات افتراضية.


### getDistance() {#getDistance--}
```
public final double getDistance()
```


يحصل أو يعيّن المسافة من النص إلى الظل.
القيمة الافتراضية هي 1.


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


يحصل أو يعيّن المسافة من النص إلى الظل.
القيمة الافتراضية هي 1.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


يحصل أو يعيّن الزاوية لوضع الظل بالنسبة للنص.
القيمة الافتراضية هي 0.


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


يحصل أو يعيّن الزاوية لوضع الظل بالنسبة للنص.
القيمة الافتراضية هي 0.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


يحصل أو يعيّن لون الظل.
القيمة الافتراضية هي الأسود.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


يحصل أو يعيّن لون الظل.
القيمة الافتراضية هي الأسود.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


يحصل أو يعيّن لون الظل.
القيمة الافتراضية هي الأسود.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


يحصل أو يعيّن شفافية الظل.
القيمة الافتراضية هي 0.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


يحصل أو يعيّن شفافية الظل.
القيمة الافتراضية هي 0.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


يحصل أو يعيّن تمويه الظل.
القيمة الافتراضية هي 4.


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


يحصل أو يعيّن تمويه الظل.
القيمة الافتراضية هي 4.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

