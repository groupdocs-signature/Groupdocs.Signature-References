---
title: "Padding"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示与元素关联的填充或边距信息。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

表示与元素关联的填充或边距信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Padding()](#Padding--) | 使用零值初始化 Padding 类的新实例。 |
| [Padding(int all)](#Padding-int-) | 使用提供的填充尺寸为所有边缘初始化 Padding 类的新实例。 |
| [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | 使用提供的填充尺寸初始化 Padding 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Empty](#Empty) | 提供一个没有填充的 Padding 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAll()](#getAll--) | 获取或设置所有边缘的 padding 值。 |
| [setAll(int value)](#setAll-int-) | 获取或设置所有边缘的 padding 值。 |
| [getLeft()](#getLeft--) | 获取或设置左边缘的 padding 值。 |
| [setLeft(int value)](#setLeft-int-) | 获取或设置左边缘的 padding 值。 |
| [getRight()](#getRight--) | 获取或设置右边缘的 padding 值。 |
| [setRight(int value)](#setRight-int-) | 获取或设置右边缘的 padding 值。 |
| [getTop()](#getTop--) | 获取或设置顶部边缘的 padding 值。 |
| [setTop(int value)](#setTop-int-) | 获取或设置顶部边缘的 padding 值。 |
| [getBottom()](#getBottom--) | 获取或设置底部边缘的 padding 值。 |
| [setBottom(int value)](#setBottom-int-) | 获取或设置底部边缘的 padding 值。 |
| [getHorizontal()](#getHorizontal--) | 获取左右边缘的合并 padding。 |
| [getVertical()](#getVertical--) | 获取上下边缘的合并 padding。 |
| [deepClone()](#deepClone--) | 获取此对象的副本。 |
| [toString()](#toString--) | 覆盖转换为字符串 |
### Padding() {#Padding--}
```
public Padding()
```


使用零值初始化 Padding 类的新实例。

### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


使用提供的填充尺寸为所有边缘初始化 Padding 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 全部 | int | 用于所有边缘的 padding 的度量单位数量。 |

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


使用提供的填充尺寸初始化 Padding 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | int | 左侧 padding 大小。 |
| 右 | int | 右侧 padding 大小。 |
| 上 | int | 顶部 padding 大小。 |
| 底部 | int | 底部 padding 大小。 |

### Empty {#Empty}
```
public static final Padding Empty
```


提供一个没有填充的 Padding 对象。

### getAll() {#getAll--}
```
public final int getAll()
```


获取或设置所有边缘的 padding 值。对左侧或顶部等任意部分边缘的更改会使此属性等于 0；

**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


获取或设置所有边缘的 padding 值。对左侧或顶部等任意部分边缘的更改会使此属性等于 0；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


获取或设置左边缘的 padding 值。

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


获取或设置左边缘的 padding 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


获取或设置右边缘的 padding 值。

**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


获取或设置右边缘的 padding 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


获取或设置顶部边缘的 padding 值。

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


获取或设置顶部边缘的 padding 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


获取或设置底部边缘的 padding 值。

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


获取或设置底部边缘的 padding 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


获取左右边缘的合并 padding。

**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


获取上下边缘的合并 padding。

**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


获取此对象的副本。

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


覆盖转换为字符串

**Returns:**
java.lang.String -
