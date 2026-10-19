---
title: "StampSignOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示印章签名选项。"
type: docs
weight: 17
url: /zh/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

表示印章签名选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | 使用默认值初始化 StampSignOptions 类的新实例。 |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | 使用对齐选项初始化 StampSignOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getStampType()](#getStampType--) | 获取或设置印章类型。 |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | 获取或设置印章类型。 |
|
|  | [getOuterLines()](#getOuterLines--) | 外部线列表，以同心圆形式呈现。 |
|
|  | [getInnerLines()](#getInnerLines--) | 内部线列表，以矩形集合形式呈现。 |
|
|  | [getBackground()](#getBackground--) | 获取或设置印章背景。 |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | 获取或设置印章背景。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 获取或设置签名的背景颜色。 |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | 获取或设置签名的背景颜色。 |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | 获取或设置签名背景刷。 |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | 获取或设置签名背景刷。 |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | 获取或设置签名的背景颜色裁剪类型。 |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | 获取或设置签名的背景颜色裁剪类型。 |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | 获取或设置签名的背景图像裁剪类型。 |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | 获取或设置签名的背景图像裁剪类型。 |
|
|  | [toString()](#toString--) | 覆盖字符串转换 |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


使用默认值初始化 StampSignOptions 类的新实例。


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


使用对齐选项初始化 StampSignOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 左 | int | 印章签名左上边缘的 x 坐标 |
|
|  | 上 | int | 印章签名左上边缘的 y 坐标 |
|
|  | 宽度 | int | 印章签名的宽度 |
|
|  | 高度 | int | 印章签名的高度 |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


获取或设置印章类型。
默认值为 Round。


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


获取或设置印章类型。
默认值为 Round。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


外部线列表，以同心圆形式呈现。


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


内部线列表，以矩形集合形式呈现。


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


获取或设置印章背景。


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


获取或设置印章背景。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


获取或设置签名的背景颜色。


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


获取或设置签名的背景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


获取或设置签名背景刷。默认值为 null。


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


获取或设置签名背景刷。默认值为 null。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


获取或设置签名的背景颜色裁剪类型。


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


获取或设置签名的背景颜色裁剪类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


获取或设置签名的背景图像裁剪类型。


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


获取或设置签名的背景图像裁剪类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换


**Returns:**
java.lang.String - 
