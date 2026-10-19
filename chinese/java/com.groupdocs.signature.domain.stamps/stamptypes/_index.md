---
title: "StampTypes"
second_title: "GroupDocs.Signature for Java API 参考"
description: "印章类型容器。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

印章类型容器。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Round](#Round) | 圆形印章类型对象。 |
|
|  | [Square](#Square) | 方形印章类型对象。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | 所有印章类型。 |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | 返回具有 pasringType 名称的印章类型。 |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | 返回具有 pasringType 名称的印章类型。 |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


圆形印章类型对象。


### Square {#Square}
```
public static final StampType Square
```


方形印章类型对象。


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


所有印章类型。


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


返回具有 pasringType 名称的印章类型。当印章名称未知时 - 抛出异常。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | parsingType | java.lang.String | 印章类型名称的源字符串。 |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


返回具有 pasringType 名称的印章类型。当印章名称未知时 - 不抛出异常，方法返回 null 值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | parsingType | java.lang.String | 印章类型名称的源字符串。 |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

