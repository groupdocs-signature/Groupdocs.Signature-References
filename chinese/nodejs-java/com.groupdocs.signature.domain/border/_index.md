---
title: "边框"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "用于保存边框线属性的实例。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

用于保存边框线属性的实例。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Border()](#Border--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDashStyle()](#getDashStyle--) | 获取或设置签名边框样式。 |
| [setDashStyle(int value)](#setDashStyle-int-) | 获取或设置签名边框样式。 |
| [getTransparency()](#getTransparency--) | 获取或设置签名边框透明度（值范围为 0.0（不透明）至 1.0（透明））。 |
| [setTransparency(double value)](#setTransparency-double-) | 获取或设置签名边框透明度（值范围为 0.0（不透明）至 1.0（透明））。 |
| [getWeight()](#getWeight--) | 获取或设置签名边框的粗细。 |
| [setWeight(double value)](#setWeight-double-) | 获取或设置签名边框的粗细。 |
| [getColor()](#getColor--) | 获取或设置签名的边框颜色。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 获取或设置签名的边框颜色。 |
| [setColor(String value)](#setColor-java.lang.String-) | 获取或设置签名的边框颜色。 |
| [getVisible()](#getVisible--) | 获取或设置边框的可见性。 |
| [setVisible(boolean value)](#setVisible-boolean-) |  |
| [deepClone()](#deepClone--) | 实现 IClonable 接口 |
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


获取或设置签名边框样式。

**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


获取或设置签名边框样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


获取或设置签名边框透明度（值范围为 0.0（不透明）至 1.0（透明））。

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


获取或设置签名边框透明度（值范围为 0.0（不透明）至 1.0（透明））。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


获取或设置签名边框的粗细。

**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


获取或设置签名边框的粗细。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


获取或设置签名的边框颜色。

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


获取或设置签名的边框颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


获取或设置签名的边框颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


获取或设置边框的可见性。

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


实现 IClonable 接口

**Returns:**
java.lang.Object - 使用相同属性新创建的 Border 实例
