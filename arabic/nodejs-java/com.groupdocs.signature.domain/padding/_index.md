---
title: "Padding"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل معلومات الحشو أو الهامش المرتبطة بالعنصر."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

يمثل معلومات الحشو أو الهامش المرتبطة بالعنصر.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Padding()](#Padding--) | إنشاء نسخة جديدة من فئة Padding باستخدام قيم صفرية. |
| [Padding(int all)](#Padding-int-) | إنشاء نسخة جديدة من فئة Padding باستخدام حجم الحشو المقدم لجميع الحواف. |
| [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | إنشاء نسخة جديدة من فئة Padding باستخدام أحجام الحشو المقدمة. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Empty](#Empty) | يوفر كائن Padding بدون حشو. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAll()](#getAll--) | يحصل أو يضبط قيمة الحشو لجميع الحواف. |
| [setAll(int value)](#setAll-int-) | يحصل أو يضبط قيمة الحشو لجميع الحواف. |
| [getLeft()](#getLeft--) | يحصل أو يضبط قيمة الحشو للحافة اليسرى. |
| [setLeft(int value)](#setLeft-int-) | يحصل أو يضبط قيمة الحشو للحافة اليسرى. |
| [getRight()](#getRight--) | يحصل أو يضبط قيمة الحشو للحافة اليمنى. |
| [setRight(int value)](#setRight-int-) | يحصل أو يضبط قيمة الحشو للحافة اليمنى. |
| [getTop()](#getTop--) | يحصل أو يضبط قيمة الحشو للحافة العليا. |
| [setTop(int value)](#setTop-int-) | يحصل أو يضبط قيمة الحشو للحافة العليا. |
| [getBottom()](#getBottom--) | يحصل أو يضبط قيمة الحشو للحافة السفلية. |
| [setBottom(int value)](#setBottom-int-) | يحصل أو يضبط قيمة الحشو للحافة السفلية. |
| [getHorizontal()](#getHorizontal--) | يحصل على الحشو المدمج للحافتين اليمنى واليسرى. |
| [getVertical()](#getVertical--) | يحصل على الحشو المدمج للحافتين العليا والسفلية. |
| [deepClone()](#deepClone--) | يحصل على نسخة من هذا الكائن. |
| [toString()](#toString--) | يتجاوز التحويل إلى سلسلة |
### Padding() {#Padding--}
```
public Padding()
```


إنشاء نسخة جديدة من فئة Padding باستخدام قيم صفرية.

### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


إنشاء نسخة جديدة من فئة Padding باستخدام حجم الحشو المقدم لجميع الحواف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الكل | int | عدد وحدات القياس التي ستُستخدم للحشو لجميع الحواف. |

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


إنشاء نسخة جديدة من فئة Padding باستخدام أحجام الحشو المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| يسار | int | حجم الحشو الأيسر. |
| يمين | int | حجم الحشو الأيمن. |
| أعلى | int | حجم الحشو العلوي. |
| أسفل | int | حجم الحشو السفلي. |

### Empty {#Empty}
```
public static final Padding Empty
```


يوفر كائن Padding بدون حشو.

### getAll() {#getAll--}
```
public final int getAll()
```


يحصل أو يضبط قيمة الحشو لجميع الحواف. تغيير أي حافة جزئية مثل اليسار أو الأعلى يجعل هذه الخاصية تساوي 0؛

**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


يحصل أو يضبط قيمة الحشو لجميع الحواف. تغيير أي حافة جزئية مثل اليسار أو الأعلى يجعل هذه الخاصية تساوي 0؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


يحصل أو يضبط قيمة الحشو للحافة اليسرى.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


يحصل أو يضبط قيمة الحشو للحافة اليسرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


يحصل أو يضبط قيمة الحشو للحافة اليمنى.

**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


يحصل أو يضبط قيمة الحشو للحافة اليمنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


يحصل أو يضبط قيمة الحشو للحافة العليا.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


يحصل أو يضبط قيمة الحشو للحافة العليا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


يحصل أو يضبط قيمة الحشو للحافة السفلية.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


يحصل أو يضبط قيمة الحشو للحافة السفلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


يحصل على الحشو المدمج للحافتين اليمنى واليسرى.

**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


يحصل على الحشو المدمج للحافتين العليا والسفلية.

**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


يحصل على نسخة من هذا الكائن.

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


يتجاوز التحويل إلى سلسلة

**Returns:**
java.lang.String -
