---
title: "الحد"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "مثيل للاحتفاظ بخصائص حدود الخط."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

مثيل للاحتفاظ بخصائص حدود الخط.

## البناؤون

| منشئ | الوصف |
| --- | --- |
| [Border()](#Border--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | يحصل أو يحدد نمط حد التوقيع. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | يحصل أو يحدد نمط حد التوقيع. |
|
|  | [getTransparency()](#getTransparency--) | يحصل أو يحدد شفافية حد التوقيع (القيمة من 0.0 (معتم) إلى 1.0 (شفاف)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | يحصل أو يحدد شفافية حد التوقيع (القيمة من 0.0 (معتم) إلى 1.0 (شفاف)). |
|
|  | [getWeight()](#getWeight--) | يحصل أو يحدد وزن حد التوقيع. |
|
|  | [setWeight(double value)](#setWeight-double-) | يحصل أو يحدد وزن حد التوقيع. |
|
|  | [getColor()](#getColor--) | يحصل أو يحدد لون حد التوقيع. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | يحصل أو يحدد لون حد التوقيع. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | يحصل أو يحدد لون حد التوقيع. |
|
|  | [getVisible()](#getVisible--) | يحصل أو يحدد رؤية الحد. |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | تنفيذ واجهة IClonable |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


يحصل أو يحدد نمط حد التوقيع.


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


يحصل أو يحدد نمط حد التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


يحصل أو يحدد شفافية حد التوقيع (القيمة من 0.0 (معتم) إلى 1.0 (شفاف)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


يحصل أو يحدد شفافية حد التوقيع (القيمة من 0.0 (معتم) إلى 1.0 (شفاف)).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


يحصل أو يحدد وزن حد التوقيع.


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


يحصل أو يحدد وزن حد التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


يحصل أو يحدد لون حد التوقيع.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


يحصل أو يحدد لون حد التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


يحصل أو يحدد لون حد التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


يحصل أو يحدد رؤية الحد.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


تنفيذ واجهة IClonable


**Returns:**
java.lang.Object - نسخة حد جديدة تم إنشاؤها بنفس الخصائص

