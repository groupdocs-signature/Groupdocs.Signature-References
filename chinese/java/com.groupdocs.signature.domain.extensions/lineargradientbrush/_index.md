---
title: "LinearGradientBrush"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示线性渐变画刷。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.domain.extensions/lineargradientbrush/
---
**Inheritance:**
java.lang.Object，[com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class LinearGradientBrush extends Brush
```

表示线性渐变画刷。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [LinearGradientBrush()](#LinearGradientBrush--) | 使用默认值初始化 LinearGradientBrush 类的新实例。 |
|
|  | [LinearGradientBrush(Color startColor, Color endColor, float angle)](#LinearGradientBrush-java.awt.Color-java.awt.Color-float-) | 初始化 LinearGradientBrush 类的新实例。 |
|
|  | [LinearGradientBrush(String startColor, String endColor, float angle)](#LinearGradientBrush-java.lang.String-java.lang.String-float-) | 初始化 LinearGradientBrush 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getStartColor()](#getStartColor--) | 获取或设置起始渐变颜色。 |
|
|  | [setStartColor(Color value)](#setStartColor-java.awt.Color-) | 获取或设置起始渐变颜色。 |
|
|  | [setStartColor(String value)](#setStartColor-java.lang.String-) | 获取或设置起始渐变颜色。 |
|
|  | [getEndColor()](#getEndColor--) | 获取或设置结束渐变颜色。 |
|
|  | [setEndColor(Color value)](#setEndColor-java.awt.Color-) | 获取或设置结束渐变颜色。 |
|
|  | [setEndColor(String value)](#setEndColor-java.lang.String-) | 获取或设置结束渐变颜色。 |
|
|  | [getAngle()](#getAngle--) | 获取或设置渐变角度。 |
|
|  | [setAngle(float value)](#setAngle-float-) | 获取或设置渐变角度。 |
|
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


使用默认值初始化 LinearGradientBrush 类的新实例。


### LinearGradientBrush(Color startColor, Color endColor, float angle) {#LinearGradientBrush-java.awt.Color-java.awt.Color-float-}
```
public LinearGradientBrush(Color startColor, Color endColor, float angle)
```


初始化 LinearGradientBrush 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | startColor | java.awt.Color | 起始颜色。 |
|
|  | endColor | java.awt.Color | 结束颜色。 |
|
|  | 角度 | 浮点数 | 角度。默认值为 0。 |
|

### LinearGradientBrush(String startColor, String endColor, float angle) {#LinearGradientBrush-java.lang.String-java.lang.String-float-}
```
public LinearGradientBrush(String startColor, String endColor, float angle)
```


初始化 LinearGradientBrush 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | startColor | java.lang.String | 起始颜色。 |
|
|  | endColor | java.lang.String | 结束颜色。 |
|
|  | 角度 | 浮点数 | 角度。默认值为 0。 |
|

### getStartColor() {#getStartColor--}
```
public final Color getStartColor()
```


获取或设置起始渐变颜色。


**Returns:**
java.awt.Color
### setStartColor(Color value) {#setStartColor-java.awt.Color-}
```
public final void setStartColor(Color value)
```


获取或设置起始渐变颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setStartColor(String value) {#setStartColor-java.lang.String-}
```
public final void setStartColor(String value)
```


获取或设置起始渐变颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getEndColor() {#getEndColor--}
```
public final Color getEndColor()
```


获取或设置结束渐变颜色。


**Returns:**
java.awt.Color
### setEndColor(Color value) {#setEndColor-java.awt.Color-}
```
public final void setEndColor(Color value)
```


获取或设置结束渐变颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setEndColor(String value) {#setEndColor-java.lang.String-}
```
public final void setEndColor(String value)
```


获取或设置结束渐变颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


获取或设置渐变角度。


**Returns:**
浮点数
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


获取或设置渐变角度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 浮点数 |  |

