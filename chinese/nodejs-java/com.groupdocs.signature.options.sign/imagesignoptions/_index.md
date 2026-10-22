---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示图像签名选项。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

表示图像签名选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageSignOptions()](#ImageSignOptions--) | 使用默认值初始化 ImageSignOptions 类的新实例。 |
| [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | 使用图像文件初始化 ImageSignOptions 类的新实例。 |
| [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | 使用图像流初始化 ImageSignOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | 获取或设置签名图像文件路径。 |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | 获取或设置签名图像文件路径。 |
| [getImageStream()](#getImageStream--) | 获取或设置签名图像流。 |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | 获取或设置签名图像流。 |
| [getLeft()](#getLeft--) | 签名在文档页上的左侧 X 位置，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType）表示。 |
| [setLeft(int value)](#setLeft-int-) | 签名在文档页上的左侧 X 位置，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType）表示。 |
| [getTop()](#getTop--) | 签名在文档页上的顶部 Y 位置，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType）表示。 |
| [setTop(int value)](#setTop-int-) | 签名在文档页上的顶部 Y 位置，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType）表示。 |
| [getWidth()](#getWidth--) | 签名在文档页上的宽度，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType）表示。 |
| [setWidth(int value)](#setWidth-int-) | 签名在文档页上的宽度，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType）表示。 |
| [getHeight()](#getHeight--) | 签名在文档页上的高度，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType）表示。 |
| [setHeight(int value)](#setHeight-int-) | 签名在文档页上的高度，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType）表示。 |
| [getLocationMeasureType()](#getLocationMeasureType--) | 左侧和顶部属性的度量类型（像素、百分比或毫米）。 |
| [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | 左侧和顶部属性的度量类型（像素、百分比或毫米）。 |
| [getSizeMeasureType()](#getSizeMeasureType--) | 宽度和高度属性的度量类型（像素、百分比或毫米）。 |
| [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | 宽度和高度属性的度量类型（像素、百分比或毫米）。 |
| [getStretch()](#getStretch--) | 文档页上的拉伸模式。 |
| [setStretch(int value)](#setStretch-int-) | 文档页上的拉伸模式。 |
| [getRotationAngle()](#getRotationAngle--) | 签名在文档页上的旋转角度（顺时针）。 |
| [setRotationAngle(int value)](#setRotationAngle-int-) | 签名在文档页上的旋转角度（顺时针）。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 签名在文档页上的水平对齐方式。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 签名在文档页上的水平对齐方式。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 签名在文档页上的垂直对齐方式。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 签名在文档页上的垂直对齐方式。 |
| [getMargin()](#getMargin--) | 获取或设置签名与文档边缘之间的间距。 |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | 获取或设置签名与文档边缘之间的间距。 |
| [getMarginMeasureType()](#getMarginMeasureType--) | 获取或设置边距的度量类型（像素、百分比或毫米）。 |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | 获取或设置边距的度量类型（像素、百分比或毫米）。 |
| [getTransparency()](#getTransparency--) | 获取或设置签名透明度（值范围为 0.0（不透明）至 1.0（透明））。 |
| [setTransparency(double value)](#setTransparency-double-) | 获取或设置签名透明度（值范围为 0.0（不透明）至 1.0（透明））。 |
| [getShapePosition()](#getShapePosition--) | 定义形状在文档布局中的呈现位置。 |
| [setShapePosition(int value)](#setShapePosition-int-) | 定义形状在文档布局中的呈现位置。 |
| [getRectangle()](#getRectangle--) | 在文档上放置图像的矩形区域。 |
| [getBorder()](#getBorder--) | 指定边框设置。 |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 指定边框设置。 |
| [toString()](#toString--) | 覆盖字符串转换。 |
| [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | 使用预定义的 Base64 图像创建 ImageSignOptions 类的新实例。 |
| [dispose()](#dispose--) | 清除内部资源。 |
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


使用默认值初始化 ImageSignOptions 类的新实例。

### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


使用图像文件初始化 ImageSignOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageFilePath | java.lang.String | 图像文件路径。 |

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


使用图像流初始化 ImageSignOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 图像流。 |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


获取或设置签名图像文件路径。如果未指定 ImageStream，则仅使用此属性。

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


获取或设置签名图像文件路径。如果未指定 ImageStream，则仅使用此属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


获取或设置签名图像流。如果指定了此属性，它将始终代替 ImageGuid 使用。

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


获取或设置签名图像流。如果指定了此属性，它将始终代替 ImageGuid 使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


签名在文档页上的左侧 X 位置，使用度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType）。(如果未指定水平对齐，则有效)。

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


签名在文档页上的左侧 X 位置，使用度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType）。(如果未指定水平对齐，则有效)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


签名在文档页上的顶部 Y 位置，使用度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType）。(如果未指定垂直对齐，则有效)。

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


签名在文档页上的顶部 Y 位置，使用度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType）。(如果未指定垂直对齐，则有效)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


签名在文档页上的宽度，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType）表示。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


签名在文档页上的宽度，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType）表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


签名在文档页上的高度，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType）表示。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


签名在文档页上的高度，以度量值（像素、百分比或毫米，参见 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType）表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


左侧和顶部属性的度量类型（像素、百分比或毫米）。

**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


左侧和顶部属性的度量类型（像素、百分比或毫米）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


宽度和高度属性的度量类型（像素、百分比或毫米）。

**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


宽度和高度属性的度量类型（像素、百分比或毫米）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


文档页上的拉伸模式。

**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


文档页上的拉伸模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


签名在文档页上的旋转角度（顺时针）。

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


签名在文档页上的旋转角度（顺时针）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


签名在文档页上的水平对齐方式。

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


签名在文档页上的水平对齐方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


签名在文档页上的垂直对齐方式。

**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


签名在文档页上的垂直对齐方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


获取或设置签名与文档边缘之间的间距。(仅在指定水平或垂直对齐时有效)。

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


获取或设置签名与文档边缘之间的间距。(仅在指定水平或垂直对齐时有效)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


获取或设置边距的度量类型（像素、百分比或毫米）。

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


获取或设置边距的度量类型（像素、百分比或毫米）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


获取或设置签名透明度（值范围为 0.0（不透明）至 1.0（透明））。默认值为 0（不透明）。

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


获取或设置签名透明度（值范围为 0.0（不透明）至 1.0（透明））。默认值为 0（不透明）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


定义形状在文档布局中的呈现位置。

**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


定义形状在文档布局中的呈现位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


在文档上放置图像的矩形区域。

**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


指定边框设置。

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


指定边框设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。

**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


使用预定义的 Base64 图像创建 ImageSignOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| base64Content | java.lang.String | 以 Base64 字符串格式的图像内容 |

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


清除内部资源。

