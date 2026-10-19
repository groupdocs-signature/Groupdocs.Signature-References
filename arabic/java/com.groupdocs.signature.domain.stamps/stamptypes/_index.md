---
title: "StampTypes"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "حاوية أنواع الطوابع."
type: docs
weight: 16
url: /ar/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

حاوية أنواع الطوابع.

## البناؤون

| منشئ | الوصف |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Round](#Round) | كائن نوع ختم دائري. |
|
|  | [Square](#Square) | كائن نوع ختم مربع. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | جميع أنواع الأختام. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | يرجع نوع الختم بالاسم pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | يرجع نوع الختم بالاسم pasringType. |
|
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


جميع أنواع الأختام.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


يرجع نوع الختم بالاسم pasringType. عندما يكون اسم الختم غير معروف - يتم إلقاء استثناء.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | parsingType | java.lang.String | سلسلة المصدر لاسم نوع الختم. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


يرجع نوع الختم بالاسم pasringType. عندما يكون اسم الختم غير معروف - لا يتم إلقاء استثناء وتعيد الطريقة قيمة null.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | parsingType | java.lang.String | سلسلة المصدر لاسم نوع الختم. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

