---
title: "الخلفية"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل مظهر الخلفية"
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

يمثل مظهر الخلفية

## البناؤون

| منشئ | الوصف |
| --- | --- |
| [Background()](#Background--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getColor()](#getColor--) | الحصول أو الضبط للون الخلفية للتوقيع. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | الحصول أو الضبط للون الخلفية للتوقيع. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | الحصول أو الضبط للون الخلفية للتوقيع. |
|
|  | [getTransparency()](#getTransparency--) | يحصل أو يحدد شفافية الخلفية (القيمة من 0.0 (معتم) إلى 1.0 (شفاف)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | يحصل أو يحدد شفافية الخلفية (القيمة من 0.0 (معتم) إلى 1.0 (شفاف)). |
|
|  | [getBrush()](#getBrush--) | يحصل أو يحدد فرشاة الخلفية. |
|
|  | [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | يحصل أو يحدد فرشاة الخلفية. |
|
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


الحصول أو الضبط للون الخلفية للتوقيع.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


الحصول أو الضبط للون الخلفية للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


الحصول أو الضبط للون الخلفية للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


يحصل أو يحدد شفافية الخلفية (القيمة من 0.0 (معتم) إلى 1.0 (شفاف)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


يحصل أو يحدد شفافية الخلفية (القيمة من 0.0 (معتم) إلى 1.0 (شفاف)).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


يحصل أو يحدد فرشاة الخلفية. القيمة الافتراضية هي null.
هذه الخاصية تتوقع مثيلًا من تطبيقات كائنات Brush.
انظر فئات Brush المختلفة.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


يحصل أو يحدد فرشاة الخلفية. القيمة الافتراضية هي null.
هذه الخاصية تتوقع مثيلًا من تطبيقات كائنات Brush.
انظر فئات Brush المختلفة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

