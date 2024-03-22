---
title: TextureBrush
second_title: GroupDocs.Signature for Java API Reference
description: Represents texture brush.
type: docs
weight: 14
url: /java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Represents texture brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextureBrush()](#TextureBrush--) | Initializes a new instance of the TextureBrush class with default values. |
| [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Initializes a new instance of the TextureBrush class with image file. |
| [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Initializes a new instance of the TextureBrush class with image stream option. |
## Methods

| Method | Description |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | Gets or sets the texture image file path. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Gets or sets the texture image file path. |
| [getImageStream()](#getImageStream--) | Gets or sets the texture image stream. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Gets or sets the texture image stream. |
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Initializes a new instance of the TextureBrush class with default values.

### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Initializes a new instance of the TextureBrush class with image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageFilePath | java.lang.String | Image file path. |

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Initializes a new instance of the TextureBrush class with image stream option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Image stream. |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Gets or sets the texture image file path. This property is used only if ImageStream is not specified.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Gets or sets the texture image file path. This property is used only if ImageStream is not specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Gets or sets the texture image stream. If this property is specified it is always used instead ImageFilePath.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Gets or sets the texture image stream. If this property is specified it is always used instead ImageFilePath.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

