---
title: "角点"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示正方形图形对象的角。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

表示正方形图形对象的角。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Corners()](#Corners--) | 使用零值初始化 Corners 类的新实例。 |
| [Corners(double all)](#Corners-double-) | 使用提供的值为所有角点初始化 Corners 类的新实例。 |
| [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | 使用提供的值初始化 Corners 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Empty](#Empty) | 提供一个没有数据的 Corners 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAll()](#getAll--) | 获取或设置所有角点的值。 |
| [setAll(double value)](#setAll-double-) | 获取或设置所有角点的值。 |
| [getTopLeft()](#getTopLeft--) | 获取或设置左上角的值。 |
| [setTopLeft(double value)](#setTopLeft-double-) | 获取或设置左上角的值。 |
| [getTopRight()](#getTopRight--) | 获取或设置右上角的值。 |
| [setTopRight(double value)](#setTopRight-double-) | 获取或设置右上角的值。 |
| [getBottomLeft()](#getBottomLeft--) | 获取或设置左下角的值。 |
| [setBottomLeft(double value)](#setBottomLeft-double-) | 获取或设置左下角的值。 |
| [getBottomRight()](#getBottomRight--) | 获取或设置右下角的值。 |
| [setBottomRight(double value)](#setBottomRight-double-) | 获取或设置右下角的值。 |
| [deepClone()](#deepClone--) | 获取此对象的副本。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 重写 equals 方法 |
| [hashCode()](#hashCode--) | 重写获取唯一哈希码值的方法 |
| [toString()](#toString--) | 重写转换为字符串的方法。 |
### Corners() {#Corners--}
```
public Corners()
```


使用零值初始化 Corners 类的新实例。

### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


使用提供的值为所有角点初始化 Corners 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 全部 | double | 用于所有角的填充值。 |

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


使用提供的值初始化 Corners 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| topLeft | double | 左上角的值。 |
| topRight | double | 右上角的值。 |
| bottomLeft | double | 左下角的值。 |
| bottomRight | double | 右下角的值。 |

### Empty {#Empty}
```
public static final Corners Empty
```


提供一个没有数据的 Corners 对象。

### getAll() {#getAll--}
```
public final double getAll()
```


获取或设置所有角的值。更改任何部分角（例如右上角）会使此属性等于 0；

**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


获取或设置所有角的值。更改任何部分角（例如右上角）会使此属性等于 0；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


获取或设置左上角的值。

**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


获取或设置左上角的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


获取或设置右上角的值。

**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


获取或设置右上角的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


获取或设置左下角的值。

**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


获取或设置左下角的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


获取或设置右下角的值。

**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


获取或设置右下角的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


获取此对象的副本。

**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


重写 equals 方法

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的实例。 |

**Returns:**
boolean - 如果对象的属性相等则返回 true。
### hashCode() {#hashCode--}
```
public int hashCode()
```


重写获取唯一哈希码值的方法

**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


重写转换为字符串的方法。

**Returns:**
java.lang.String -
