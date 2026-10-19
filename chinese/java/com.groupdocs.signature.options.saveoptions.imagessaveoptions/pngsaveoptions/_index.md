---
title: "PngSaveOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "Png 图像文档的保存选项。"
type: docs
weight: 22
url: /zh/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

Png 图像文档的保存选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PngSaveOptions()](#PngSaveOptions--) | 创建具有默认值的 PngSaveOptions。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getBitDepth()](#getBitDepth--) | 位深度。 |
|
|  | [setBitDepth(byte value)](#setBitDepth-byte-) | 位深度。 |
|
|  | [getColorType()](#getColorType--) | 获取或设置该类型的 |
PngColorType
.
|
|  | [setColorType(int value)](#setColorType-int-) | 获取或设置该类型的 |
PngColorType
.
|
|  | [getCompressionLevel()](#getCompressionLevel--) | png 图像压缩级别，范围为 0-9，其中 9 为最高压缩 |
而 0 为存储模式。
|
|  | [setCompressionLevel(int value)](#setCompressionLevel-int-) | png 图像压缩级别，范围为 0-9，其中 9 为最高压缩 |
而 0 为存储模式。
|
|  | [getFilterType()](#getFilterType--) | 获取或设置过滤器类型 |
PngFilterType
在 png 文件保存过程中使用。
|
|  | [setFilterType(int value)](#setFilterType-int-) | 获取或设置过滤器类型 |
PngFilterType
在 png 文件保存过程中使用。
|
|  | [getProgressive()](#getProgressive--) | 获取或设置一个值，指示此 PngSaveOptions 是否为渐进式。 |
|
|  | [setProgressive(boolean value)](#setProgressive-boolean-) | 获取或设置一个值，指示此 PngSaveOptions 是否为渐进式。 |
|
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


创建具有默认值的 PngSaveOptions。


### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


位深度。


**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


位深度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


获取或设置该类型的
PngColorType
.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


获取或设置该类型的
PngColorType
.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


png 图像压缩级别，范围为 0-9，其中 9 为最高压缩
而 0 为存储模式。


**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


png 图像压缩级别，范围为 0-9，其中 9 为最高压缩
而 0 为存储模式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


获取或设置过滤器类型
PngFilterType
在 png 文件保存过程中使用。


**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


获取或设置过滤器类型
PngFilterType
在 png 文件保存过程中使用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


获取或设置一个值，指示此 PngSaveOptions 是否为渐进式。


**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


获取或设置一个值，指示此 PngSaveOptions 是否为渐进式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

