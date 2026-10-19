---
title: "JpegSaveOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "Jpeg 图像文档的保存选项。"
type: docs
weight: 19
url: /zh/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Jpeg 图像文档的保存选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | 创建具有默认值的 JpegSaveOptions。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | 获取或设置无损 jpeg 图像的每通道位数。 |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | 获取或设置无损 jpeg 图像的每通道位数。 |
|
|  | [getColorType()](#getColorType--) | 获取或设置 jpeg 图像的颜色类型。 |
|
|  | [setColorType(int value)](#setColorType-int-) | 获取或设置 jpeg 图像的颜色类型。 |
|
|  | [getComment()](#getComment--) | 获取或设置 jpeg 文件注释。 |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | 获取或设置 jpeg 文件注释。 |
|
|  | [getCompressionType()](#getCompressionType--) | 获取或设置压缩类型。 |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | 获取或设置压缩类型。 |
|
|  | [getQuality()](#getQuality--) | 获取或设置图像质量。 |
|
|  | [setQuality(int value)](#setQuality-int-) | 获取或设置图像质量。 |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | 获取或设置样本舍入模式，以将 8 位值适配为 n 位值 |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 获取或设置样本舍入模式，以将 8 位值适配为 n 位值 |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | 获取或设置已签署文档的文件格式。 |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 获取或设置已签署文档的文件格式。 |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


创建具有默认值的 JpegSaveOptions。


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


获取或设置无损 jpeg 图像的每通道位数。
现在我们支持每通道 2 到 8 位。


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


获取或设置无损 jpeg 图像的每通道位数。
现在我们支持每通道 2 到 8 位。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


获取或设置 jpeg 图像的颜色类型。


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


获取或设置 jpeg 图像的颜色类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


获取或设置 jpeg 文件注释。


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


获取或设置 jpeg 文件注释。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


获取或设置压缩类型。


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


获取或设置压缩类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


获取或设置图像质量。


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


获取或设置图像质量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


获取或设置样本舍入模式，以将 8 位值适配为 n 位值
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


获取或设置样本舍入模式，以将 8 位值适配为 n 位值
JpegOptions.BitsPerChannel.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


获取或设置已签署文档的文件格式。此选项类未使用，已隐藏。


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


获取或设置已签署文档的文件格式。此选项类未使用，已隐藏。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

