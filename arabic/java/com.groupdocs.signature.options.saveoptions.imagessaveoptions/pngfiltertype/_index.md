---
title: "PngFilterType"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل نوع مرشح صورة PNG."
type: docs
weight: 21
url: /ar/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

يمثل نوع مرشح صورة PNG.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [None](#None) | المرشح null-filter، يعني عدم وجود تصفية لصفوف بيانات الصورة. |
|
|  | [Sub](#Sub) | المرشح sub filter، يعني أنه سيتم تطبيق تصفية طرحية على بيانات الصورة. |
|
|  | [Up](#Up) | المرشح up filter، يعني أنه سيتم تطبيق تصفية طرح صف بصف. |
|
|  | [Avg](#Avg) | المرشح avg filter، يعني أن تصفية المتوسط ستُطبق على بيانات الصورة. |
|
|  | [Paeth](#Paeth) | المرشح path predictor. |
|
|  | [Adaptive](#Adaptive) | التصفية التكيفية، يعني أن عملية الحفظ ستختار الأنسب من الفلاتر |
لكل صف بيانات.
|
### None {#None}
```
public static final int None
```


المرشح null-filter، يعني عدم وجود تصفية لصفوف بيانات الصورة.


### Sub {#Sub}
```
public static final int Sub
```


المرشح sub filter، يعني أنه سيتم تطبيق تصفية طرحية على بيانات الصورة.


### Up {#Up}
```
public static final int Up
```


المرشح up filter، يعني أنه سيتم تطبيق تصفية طرح صف بصف.


### Avg {#Avg}
```
public static final int Avg
```


المرشح avg filter، يعني أن تصفية المتوسط ستُطبق على بيانات الصورة.


### Paeth {#Paeth}
```
public static final int Paeth
```


المرشح path predictor.


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


التصفية التكيفية، يعني أن عملية الحفظ ستختار الأنسب من الفلاتر
لكل صف بيانات. أفضل ضغط، أبطأ وقت تنفيذ.


