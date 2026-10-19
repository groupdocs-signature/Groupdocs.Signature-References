---
title: "TextShadow"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示文本签名的文字阴影属性。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

表示文本签名的文字阴影属性。
结果可能因签名类型和文档格式而异。
建议在所有受支持的文档类型中将 TextShadow 与 TextAsImage 签名一起使用，
还可以使用简单的 TextSignature，并将 TextSignature 作为 Cells (.xslx) 和 Slides (.pptx) 的水印。
也推荐在 Words (.docx) 中使用简单的 TextSignature，但功能有限。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | 使用默认选项创建 TextShadow。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getDistance()](#getDistance--) | 获取或设置文本到阴影的距离。 |
|
|  | [setDistance(double value)](#setDistance-double-) | 获取或设置文本到阴影的距离。 |
|
|  | [getAngle()](#getAngle--) | 获取或设置阴影相对于文本的放置角度。 |
|
|  | [setAngle(double value)](#setAngle-double-) | 获取或设置阴影相对于文本的放置角度。 |
|
|  | [getColor()](#getColor--) | 获取或设置阴影的颜色。 |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 获取或设置阴影的颜色。 |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | 获取或设置阴影的颜色。 |
|
|  | [getTransparency()](#getTransparency--) | 获取或设置阴影的透明度。 |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 获取或设置阴影的透明度。 |
|
|  | [getBlur()](#getBlur--) | 获取或设置阴影的模糊程度。 |
|
|  | [setBlur(double value)](#setBlur-double-) | 获取或设置阴影的模糊程度。 |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


使用默认选项创建 TextShadow。


### getDistance() {#getDistance--}
```
public final double getDistance()
```


获取或设置文本到阴影的距离。
默认值为 1。


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


获取或设置文本到阴影的距离。
默认值为 1。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


获取或设置阴影相对于文本的放置角度。
默认值为 0。


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


获取或设置阴影相对于文本的放置角度。
默认值为 0。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


获取或设置阴影的颜色。
默认值为黑色。


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


获取或设置阴影的颜色。
默认值为黑色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


获取或设置阴影的颜色。
默认值为黑色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


获取或设置阴影的透明度。
默认值为 0。


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


获取或设置阴影的透明度。
默认值为 0。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


获取或设置阴影的模糊程度。
默认值为 4。


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


获取或设置阴影的模糊程度。
默认值为 4。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

