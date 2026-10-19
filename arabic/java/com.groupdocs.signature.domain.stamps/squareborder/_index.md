---
title: "SquareBorder"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "مثيل للاحتفاظ بخصائص خط الحدود لخط الطابع المربع."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.domain.stamps/squareborder/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.Border](../../com.groupdocs.signature.domain/border)
```
public class SquareBorder extends Border
```

مثيل للاحتفاظ بخصائص خط الحدود لخط الطابع المربع.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [SquareBorder(double radius)](#SquareBorder-double-) | ينشئ SquareBorderLine مع نصف قطر الزاوية المدورة. |
|
|  | [SquareBorder(Corners corners)](#SquareBorder-com.groupdocs.signature.domain.stamps.Corners-) | ينشئ SquareBorderLine مع قيم نصف قطر الزاوية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getRadius()](#getRadius--) | يحصل أو يضبط نصف قطر زوايا المربع. |
|
|  | [setRadius(Corners value)](#setRadius-com.groupdocs.signature.domain.stamps.Corners-) | يحصل أو يضبط نصف قطر زوايا المربع. |
|
### SquareBorder(double radius) {#SquareBorder-double-}
```
public SquareBorder(double radius)
```


ينشئ SquareBorderLine مع نصف قطر الزاوية المدورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نصف القطر | double | نصف قطر زوايا المربع. |
|

### SquareBorder(Corners corners) {#SquareBorder-com.groupdocs.signature.domain.stamps.Corners-}
```
public SquareBorder(Corners corners)
```


ينشئ SquareBorderLine مع قيم نصف قطر الزاوية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | corners | [Corners](../../com.groupdocs.signature.domain.stamps/corners) | نصف قطر زوايا المربع. |
|

### getRadius() {#getRadius--}
```
public final Corners getRadius()
```


يحصل أو يضبط نصف قطر زوايا المربع.


**Returns:**
[Corners](../../com.groupdocs.signature.domain.stamps/corners)
### setRadius(Corners value) {#setRadius-com.groupdocs.signature.domain.stamps.Corners-}
```
public final void setRadius(Corners value)
```


يحصل أو يضبط نصف قطر زوايا المربع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Corners](../../com.groupdocs.signature.domain.stamps/corners) |  |

