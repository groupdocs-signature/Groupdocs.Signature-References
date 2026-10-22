---
title: "زوايا"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثّل زوايا كائن رسومي مربع."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

يمثّل زوايا كائن رسومي مربع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Corners()](#Corners--) | يقوم بتهيئة نسخة جديدة من الفئة Corners باستخدام قيم صفرية. |
| [Corners(double all)](#Corners-double-) | يقوم بتهيئة نسخة جديدة من الفئة Corners باستخدام القيمة المقدمة لجميع الزوايا. |
| [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | يقوم بتهيئة نسخة جديدة من الفئة Corners باستخدام القيم المقدمة. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Empty](#Empty) | يوفر كائن Corners بدون بيانات. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAll()](#getAll--) | يحصل أو يعيّن القيمة لجميع الزوايا. |
| [setAll(double value)](#setAll-double-) | يحصل أو يعيّن القيمة لجميع الزوايا. |
| [getTopLeft()](#getTopLeft--) | يحصل أو يعيّن قيمة الزاوية العلوية اليسرى. |
| [setTopLeft(double value)](#setTopLeft-double-) | يحصل أو يعيّن قيمة الزاوية العلوية اليسرى. |
| [getTopRight()](#getTopRight--) | يحصل أو يعيّن قيمة الزاوية العلوية اليمنى. |
| [setTopRight(double value)](#setTopRight-double-) | يحصل أو يعيّن قيمة الزاوية العلوية اليمنى. |
| [getBottomLeft()](#getBottomLeft--) | يحصل أو يعيّن قيمة الزاوية السفلية اليسرى. |
| [setBottomLeft(double value)](#setBottomLeft-double-) | يحصل أو يعيّن قيمة الزاوية السفلية اليسرى. |
| [getBottomRight()](#getBottomRight--) | يحصل أو يعيّن قيمة الزاوية السفلية اليمنى. |
| [setBottomRight(double value)](#setBottomRight-double-) | يحصل أو يعيّن قيمة الزاوية السفلية اليمنى. |
| [deepClone()](#deepClone--) | يحصل على نسخة من هذا الكائن. |
| [equals(Object obj)](#equals-java.lang.Object-) | تجاوز طريقة equals |
| [hashCode()](#hashCode--) | يتجاوز الحصول على قيمة تجزئة فريدة |
| [toString()](#toString--) | يتجاوز التحويل إلى سلسلة. |
### Corners() {#Corners--}
```
public Corners()
```


يقوم بتهيئة نسخة جديدة من الفئة Corners باستخدام قيم صفرية.

### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


يقوم بتهيئة نسخة جديدة من الفئة Corners باستخدام القيمة المقدمة لجميع الزوايا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الكل | double | القيمة التي ستُستخدم للتوسيط لجميع الزوايا. |

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


يقوم بتهيئة نسخة جديدة من الفئة Corners باستخدام القيم المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| topLeft | double | قيمة الزاوية العلوية اليسرى. |
| topRight | double | قيمة الزاوية العلوية اليمنى. |
| bottomLeft | double | قيمة الزاوية السفلية اليسرى. |
| bottomRight | double | قيمة الزاوية السفلية اليمنى. |

### Empty {#Empty}
```
public static final Corners Empty
```


يوفر كائن Corners بدون بيانات.

### getAll() {#getAll--}
```
public final double getAll()
```


يحصل أو يعيّن القيمة لجميع الزوايا. تغيير أي زاوية جزئية مثل top right يجعل هذه الخاصية تساوي 0؛

**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


يحصل أو يعيّن القيمة لجميع الزوايا. تغيير أي زاوية جزئية مثل top right يجعل هذه الخاصية تساوي 0؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


يحصل أو يعيّن قيمة الزاوية العلوية اليسرى.

**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


يحصل أو يعيّن قيمة الزاوية العلوية اليسرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


يحصل أو يعيّن قيمة الزاوية العلوية اليمنى.

**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


يحصل أو يعيّن قيمة الزاوية العلوية اليمنى.

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
| obj | java.lang.Object | نسخة للمقارنة معها. |

**Returns:**
boolean - يُرجِع true إذا كانت خصائص الكائنات متساوية.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يتجاوز الحصول على قيمة تجزئة فريدة

**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


يتجاوز التحويل إلى سلسلة.

**Returns:**
java.lang.String -
