---
title: "ImageAppearance"
second_title: "GroupDocs.Signature for Java API 参考"
description: "描述图像签名的扩展外观特性。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.options.appearances/imageappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class ImageAppearance extends SignatureAppearance
```

描述图像签名的扩展外观特性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ImageAppearance()](#ImageAppearance--) | 使用默认值创建实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getGrayscale()](#getGrayscale--) | 如果需要灰度过滤器，请将此标志设置为 true。 |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | 如果需要灰度过滤器，请将此标志设置为 true。 |
|
|  | [getBrightness()](#getBrightness--) | 获取或设置图像亮度。 |
|
|  | [setBrightness(float value)](#setBrightness-float-) | 获取或设置图像亮度。 |
|
|  | [getContrast()](#getContrast--) | 获取或设置图像对比度。 |
|
|  | [setContrast(float value)](#setContrast-float-) | 获取或设置图像对比度。 |
|
|  | [getGammaCorrection()](#getGammaCorrection--) | 获取或设置图像伽马值。 |
|
|  | [setGammaCorrection(float value)](#setGammaCorrection-float-) | 获取或设置图像伽马值。 |
|
### ImageAppearance() {#ImageAppearance--}
```
public ImageAppearance()
```


使用默认值创建实例。


### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


如果需要灰度过滤器，请将此标志设置为 true。


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


如果需要灰度过滤器，请将此标志设置为 true。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getBrightness() {#getBrightness--}
```
public final float getBrightness()
```


获取或设置图像亮度。
默认值为 1，对应图像的原始亮度。


**Returns:**
浮点数
### setBrightness(float value) {#setBrightness-float-}
```
public final void setBrightness(float value)
```


获取或设置图像亮度。
默认值为 1，对应图像的原始亮度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 浮点数 |  |

### getContrast() {#getContrast--}
```
public final float getContrast()
```


获取或设置图像对比度。
默认值为 1，对应图像的原始对比度。


**Returns:**
浮点数
### setContrast(float value) {#setContrast-float-}
```
public final void setContrast(float value)
```


获取或设置图像对比度。
默认值为 1，对应图像的原始对比度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 浮点数 |  |

### getGammaCorrection() {#getGammaCorrection--}
```
public final float getGammaCorrection()
```


获取或设置图像伽马值。
默认值为 1，对应图像的原始伽马值。


**Returns:**
浮点数
### setGammaCorrection(float value) {#setGammaCorrection-float-}
```
public final void setGammaCorrection(float value)
```


获取或设置图像伽马值。
默认值为 1，对应图像的原始伽马值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 浮点数 |  |

