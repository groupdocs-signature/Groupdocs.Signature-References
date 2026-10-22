---
title: "PngSaveOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "Png 保存选项用于图像文档。"
type: docs
weight: 22
url: /zh/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

Png 保存选项用于图像文档。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PngSaveOptions()](#PngSaveOptions--) | 创建 PngSaveOptions 并使用默认值。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitDepth()](#getBitDepth--) | 位深度。 |
| [setBitDepth(byte value)](#setBitDepth-byte-) | 位深度。 |
| [getColorType()](#getColorType--) | 获取或设置 PngColorType 的类型。 |
| [setColorType(int value)](#setColorType-int-) | 获取或设置 PngColorType 的类型。 |
| [getCompressionLevel()](#getCompressionLevel--) | png 图像压缩级别在 0-9 范围内，9 为最高压缩，0 为存储模式。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | png 图像压缩级别在 0-9 范围内，9 为最高压缩，0 为存储模式。 |
| [getFilterType()](#getFilterType--) | 获取或设置在 png 文件保存过程中使用的过滤器类型 PngFilterType。 |
| [setFilterType(int value)](#setFilterType-int-) | 获取或设置在 png 文件保存过程中使用的过滤器类型 PngFilterType。 |
| [getProgressive()](#getProgressive--) | 获取或设置一个值，指示此 PngSaveOptions 是否为渐进式。 |
| [setProgressive(boolean value)](#setProgressive-boolean-) | 获取或设置一个值，指示此 PngSaveOptions 是否为渐进式。 |
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


创建 PngSaveOptions 并使用默认值。

### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


位深度。

**Returns:**
字节
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


位深度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 字节 |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


获取或设置 PngColorType 的类型。

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


获取或设置 PngColorType 的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


png 图像压缩级别在 0-9 范围内，9 为最高压缩，0 为存储模式。

**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


png 图像压缩级别在 0-9 范围内，9 为最高压缩，0 为存储模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


获取或设置在 png 文件保存过程中使用的过滤器类型 PngFilterType。

**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


获取或设置在 png 文件保存过程中使用的过滤器类型 PngFilterType。

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

