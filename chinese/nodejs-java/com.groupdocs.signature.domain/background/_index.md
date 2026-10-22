---
title: "背景"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示背景外观"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

表示背景外观
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Background()](#Background--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 获取或设置签名的背景颜色。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 获取或设置签名的背景颜色。 |
| [setColor(String value)](#setColor-java.lang.String-) | 获取或设置签名的背景颜色。 |
| [getTransparency()](#getTransparency--) | 获取或设置背景透明度（值范围为 0.0（不透明）至 1.0（透明））。 |
| [setTransparency(double value)](#setTransparency-double-) | 获取或设置背景透明度（值范围为 0.0（不透明）至 1.0（透明））。 |
| [getBrush()](#getBrush--) | 获取或设置背景画刷。 |
| [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | 获取或设置背景画刷。 |
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


获取或设置签名的背景颜色。

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


获取或设置签名的背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


获取或设置签名的背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


获取或设置背景透明度（值范围为 0.0（不透明）至 1.0（透明））。

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


获取或设置背景透明度（值范围为 0.0（不透明）至 1.0（透明））。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


获取或设置背景画刷。默认值为 null。此属性期望 Brush 对象实现的实例。参见不同的 Brush 类。

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


获取或设置背景画刷。默认值为 null。此属性期望 Brush 对象实现的实例。参见不同的 Brush 类。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

