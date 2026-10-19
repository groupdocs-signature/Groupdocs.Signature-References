---
title: "Corners"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل زوايا كائن رسومي مربع."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

يمثل زوايا كائن رسومي مربع.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [Corners()](#Corners--) | يُنشئ مثيلاً جديدًا من فئة Corners باستخدام قيم صفرية. |
|
|  | [Corners(double all)](#Corners-double-) | يُنشئ مثيلاً جديدًا من فئة Corners باستخدام القيمة المقدمة لجميع الزوايا. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | يُنشئ مثيلاً جديدًا من فئة Corners باستخدام القيم المقدمة. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Empty](#Empty) | يوفر كائن Corners بدون بيانات. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAll()](#getAll--) | الحصول أو الضبط للقيمة لجميع الزوايا. |
|
|  | [setAll(double value)](#setAll-double-) | الحصول أو الضبط للقيمة لجميع الزوايا. |
|
|  | [getTopLeft()](#getTopLeft--) | الحصول أو الضبط لقيمة الزاوية العلوية اليسرى. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | الحصول أو الضبط لقيمة الزاوية العلوية اليسرى. |
|
|  | [getTopRight()](#getTopRight--) | يحصل أو يعيّن قيمة الزاوية العليا اليمنى. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | يحصل أو يعيّن قيمة الزاوية العليا اليمنى. |
|
|  | [getBottomLeft()](#getBottomLeft--) | يحصل أو يعيّن قيمة الزاوية السفلية اليسرى. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | يحصل أو يعيّن قيمة الزاوية السفلية اليسرى. |
|
|  | [getBottomRight()](#getBottomRight--) | يحصل أو يعيّن قيمة الزاوية السفلية اليمنى. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | يحصل أو يعيّن قيمة الزاوية السفلية اليمنى. |
|
|  | [deepClone()](#deepClone--) | يحصل على نسخة من هذا الكائن. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | تجاوز طريقة equals |
|
|  | [hashCode()](#hashCode--) | يتجاوز الحصول على قيمة hash code الفريدة |
|
|  | [toString()](#toString--) | يتجاوز التحويل إلى string. |
|
### Corners() {#Corners--}
```
public Corners()
```


يُنشئ مثيلاً جديدًا من فئة Corners باستخدام قيم صفرية.


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


يُنشئ مثيلاً جديدًا من فئة Corners باستخدام القيمة المقدمة لجميع الزوايا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الكل | double | القيمة التي ستُستخدم كحشو لجميع الزوايا. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


يُنشئ مثيلاً جديدًا من فئة Corners باستخدام القيم المقدمة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | topLeft | double | قيمة الزاوية العليا اليسرى. |
|
|  | topRight | double | قيمة الزاوية العليا اليمنى. |
|
|  | bottomLeft | double | قيمة الزاوية السفلية اليسرى. |
|
|  | bottomRight | double | قيمة الزاوية السفلية اليمنى. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


يوفر كائن Corners بدون بيانات.


### getAll() {#getAll--}
```
public final double getAll()
```


الحصول أو الضبط للقيمة لجميع الزوايا.
تغيير أي زاوية جزئية مثل الزاوية العليا اليمنى يجعل هذه الخاصية تساوي 0؛


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


الحصول أو الضبط للقيمة لجميع الزوايا.
تغيير أي زاوية جزئية مثل الزاوية العليا اليمنى يجعل هذه الخاصية تساوي 0؛


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


الحصول أو الضبط لقيمة الزاوية العلوية اليسرى.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


الحصول أو الضبط لقيمة الزاوية العلوية اليسرى.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


يحصل أو يعيّن قيمة الزاوية العليا اليمنى.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


يحصل أو يعيّن قيمة الزاوية العليا اليمنى.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


يحصل أو يعيّن قيمة الزاوية السفلية اليسرى.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


يحصل أو يعيّن قيمة الزاوية السفلية اليسرى.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


يحصل أو يعيّن قيمة الزاوية السفلية اليمنى.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


يحصل أو يعيّن قيمة الزاوية السفلية اليمنى.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


يحصل على نسخة من هذا الكائن.


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تجاوز طريقة equals


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثيل للمقارنة معه. |
|

**Returns:**
boolean - يُعيد true إذا كانت خصائص الكائنات متساوية.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يتجاوز الحصول على قيمة hash code الفريدة


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


يتجاوز التحويل إلى string.


**Returns:**
java.lang.String -
