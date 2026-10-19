---
title: "BmpSaveOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "Bmp 图像文档的保存选项。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bmpsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class BmpSaveOptions extends ImageSaveOptions
```

Bmp 图像文档的保存选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [BmpSaveOptions()](#BmpSaveOptions--) | 使用默认值创建 BmpSaveOptions。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getBitsPerPixel()](#getBitsPerPixel--) | 获取或设置图像每像素位数。 |
|
|  | [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | 获取或设置图像每像素位数。 |
|
|  | [getCompression()](#getCompression--) | 获取或设置压缩方式。 |
|
|  | [setCompression(int value)](#setCompression-int-) | 获取或设置压缩方式。 |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 获取或设置水平分辨率。 |
|
|  | [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 获取或设置水平分辨率。 |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 获取或设置垂直分辨率。 |
|
|  | [setVerticalResolution(double value)](#setVerticalResolution-double-) | 获取或设置垂直分辨率。 |
|
### BmpSaveOptions() {#BmpSaveOptions--}
```
public BmpSaveOptions()
```


使用默认值创建 BmpSaveOptions。


### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


获取或设置图像每像素位数。


**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


获取或设置图像每像素位数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


获取或设置压缩方式。参见 [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression)。


**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


获取或设置压缩方式。参见 [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final double getHorizontalResolution()
```


获取或设置水平分辨率。注意，由于四舍五入，结果
分辨率可能与传入的值略有差异。


**Returns:**
double
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public final void setHorizontalResolution(double value)
```


获取或设置水平分辨率。注意，由于四舍五入，结果
分辨率可能与传入的值略有差异。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final double getVerticalResolution()
```


获取或设置垂直分辨率。注意，由于四舍五入，结果
分辨率可能与传入的值略有差异。


**Returns:**
double
### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public final void setVerticalResolution(double value)
```


获取或设置垂直分辨率。注意，由于四舍五入，结果
分辨率可能与传入的值略有差异。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

