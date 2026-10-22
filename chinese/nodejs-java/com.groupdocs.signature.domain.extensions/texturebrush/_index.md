---
title: "TextureBrush"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示纹理画刷。"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

表示纹理画刷。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextureBrush()](#TextureBrush--) | 使用默认值初始化 TextureBrush 类的新实例。 |
| [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | 使用图像文件初始化 TextureBrush 类的新实例。 |
| [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | 使用图像流选项初始化 TextureBrush 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | 获取或设置纹理图像文件路径。 |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | 获取或设置纹理图像文件路径。 |
| [getImageStream()](#getImageStream--) | 获取或设置纹理图像流。 |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | 获取或设置纹理图像流。 |
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


使用默认值初始化 TextureBrush 类的新实例。

### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


使用图像文件初始化 TextureBrush 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageFilePath | java.lang.String | 图像文件路径。 |

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


使用图像流选项初始化 TextureBrush 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 图像流。 |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


获取或设置纹理图像文件路径。如果未指定 ImageStream，则仅使用此属性。

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


获取或设置纹理图像文件路径。如果未指定 ImageStream，则仅使用此属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


获取或设置纹理图像流。如果指定了此属性，则始终使用它而不是 ImageFilePath。

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


获取或设置纹理图像流。如果指定了此属性，则始终使用它而不是 ImageFilePath。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.io.InputStream |  |

