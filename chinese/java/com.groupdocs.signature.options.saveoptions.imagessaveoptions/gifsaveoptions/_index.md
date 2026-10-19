---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "Gif 格式图像文档的保存选项。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Gif 格式图像文档的保存选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [GifSaveOptions()](#GifSaveOptions--) | 使用默认值创建 GifSaveOptions。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | 获取或设置 GIF 背景颜色索引。 |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | 获取或设置 GIF 背景颜色索引。 |
|
|  | [getColorResolution()](#getColorResolution--) | 获取或设置 GIF 颜色分辨率。 |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | 获取或设置 GIF 颜色分辨率。 |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | 获取或设置一个值，指示是否应用调色板校正。 |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | 获取或设置一个值，指示是否应用调色板校正。 |
|
|  | [hasTrailer()](#hasTrailer--) | 获取或设置一个值，指示 GIF 是否具有尾部。 |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | 获取或设置一个值，指示 GIF 是否具有尾部。 |
|
|  | [getInterlaced()](#getInterlaced--) | 如果图像应交错则为 True。 |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | 如果图像应交错则为 True。 |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | 获取或设置一个值，指示调色板条目是否已排序。 |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | 获取或设置一个值，指示调色板条目是否已排序。 |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | 获取或设置 GIF 像素宽高比。 |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | 获取或设置 GIF 像素宽高比。 |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


使用默认值创建 GifSaveOptions。


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


获取或设置 GIF 背景颜色索引。


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


获取或设置 GIF 背景颜色索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


获取或设置 GIF 颜色分辨率。

<br />

*** ** * ** ***

Color Resolution - 原始图像每个原色可用的位数减 1。此值表示用于选择图形颜色的整个调色板的大小，而不是图形实际使用的颜色数量。例如，如果此字段的值为 3，则原始图像的调色板每个原色有 4 位可用于创建图像。即使源机器上并非所有调色板颜色都可用，也应设置此值以指示原始调色板的丰富程度。

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


获取或设置 GIF 颜色分辨率。

<br />

*** ** * ** ***

Color Resolution - 原始图像每个原色可用的位数减 1。此值表示用于选择图形颜色的整个调色板的大小，而不是图形实际使用的颜色数量。例如，如果此字段的值为 3，则原始图像的调色板每个原色有 4 位可用于创建图像。即使源机器上并非所有调色板颜色都可用，也应设置此值以指示原始调色板的丰富程度。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


获取或设置一个值，指示是否应用调色板校正。

<br />

*** ** * ** ***

调色板校正意味着每当图像导出为 GIF 时，源图像的颜色将被分析以构建最匹配的调色板（如果图像调色板不存在或在选项中未指定）。分析过程需要一些时间，但输出图像将拥有最佳匹配的颜色调色板，视觉效果更佳。

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


获取或设置一个值，指示是否应用调色板校正。

<br />

*** ** * ** ***

调色板校正意味着每当图像导出为 GIF 时，源图像的颜色将被分析以构建最匹配的调色板（如果图像调色板不存在或在选项中未指定）。分析过程需要一些时间，但输出图像将拥有最佳匹配的颜色调色板，视觉效果更佳。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


获取或设置一个值，指示 GIF 是否具有尾部。


**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


获取或设置一个值，指示 GIF 是否具有尾部。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


如果图像应交错则为 True。


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


如果图像应交错则为 True。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


获取或设置一个值，指示调色板条目是否已排序。


**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


获取或设置一个值，指示调色板条目是否已排序。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


获取或设置 GIF 像素宽高比。

<br />

*** ** * ** ***

Pixel Aspect Ratio - 用于计算原始图像像素宽高比近似值的因子。如果该字段的值不为 0，则根据公式计算该宽高比的近似值：Aspect Ratio = (Pixel Aspect Ratio + 15) / 64。Pixel Aspect Ratio 定义为像素宽度除以高度的商。此字段的取值范围允许以 1/64 为增量指定最宽像素为 4:1 到最窄像素为 1:4。取值：0 - 未提供宽高比信息。1..255 - 用于计算的值。

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


获取或设置 GIF 像素宽高比。

<br />

*** ** * ** ***

Pixel Aspect Ratio - 用于计算原始图像像素宽高比近似值的因子。如果该字段的值不为 0，则根据公式计算该宽高比的近似值：Aspect Ratio = (Pixel Aspect Ratio + 15) / 64。Pixel Aspect Ratio 定义为像素宽度除以高度的商。此字段的取值范围允许以 1/64 为增量指定最宽像素为 4:1 到最窄像素为 1:4。取值：0 - 未提供宽高比信息。1..255 - 用于计算的值。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

