---
title: "StampTypes"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "حاوية أنواع الطوابع."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

حاوية أنواع الطوابع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Round](#Round) | كائن نوع ختم دائري. |
| [Square](#Square) | كائن نوع ختم مربع. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | جميع أنواع الختم. |
| [parse(String parsingType)](#parse-java.lang.String-) | يُرجِع نوع الختم بالاسم pasringType. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | يُرجِع نوع الختم بالاسم pasringType. |
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


كائن نوع ختم دائري.

### Square {#Square}
```
public static final StampType Square
```


كائن نوع ختم مربع.

### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


جميع أنواع الختم.

**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


يُرجِع نوع الختم بالاسم pasringType. عندما يكون اسم الختم غير معروف - يتم رمي استثناء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة المصدر لاسم نوع الختم. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


يُرجِع نوع الختم بالاسم pasringType. عندما يكون اسم الختم غير معروف - لا يتم رمي استثناء وتُرجِع الطريقة قيمة null.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة المصدر لاسم نوع الختم. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
