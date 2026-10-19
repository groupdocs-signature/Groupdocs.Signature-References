---
title: "TextSignOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示文本签名选项。"
type: docs
weight: 18
url: /zh/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

表示文本签名选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | 使用默认值初始化 SignTextOptions 类的新实例。 |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | 使用文本初始化 SignTextOptions 类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getLeft()](#getLeft--) | 文档页面上签名的左侧 X 位置（以测量值表示） |
(像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 属性)。
|
|  | [setLeft(int value)](#setLeft-int-) | 文档页面上签名的左侧 X 位置（以测量值表示） |
(像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 属性)。
|
|  | [getTop()](#getTop--) | 文档页面上签名的顶部 Y 位置（以测量值表示） |
(像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 属性)。
|
|  | [setTop(int value)](#setTop-int-) | 文档页面上签名的顶部 Y 位置（以测量值表示） |
(像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 属性)。
|
|  | [getWidth()](#getWidth--) | 文档页面上签名的宽度（以测量值表示） |
（像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 属性）。
|
|  | [setWidth(int value)](#setWidth-int-) | 文档页面上签名的宽度（以测量值表示） |
（像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 属性）。
|
|  | [getHeight()](#getHeight--) | 文档页面上签名的高度（以测量值表示） |
（像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 属性）。
|
|  | [setHeight(int value)](#setHeight-int-) | 文档页面上签名的高度（以测量值表示） |
（像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 属性）。
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | 宽度和高度属性的测量类型（像素、百分比或毫米）。 |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | 宽度和高度属性的测量类型（像素、百分比或毫米）。 |
|
|  | [getStretch()](#getStretch--) | 文档页面上的拉伸模式。 |
|
|  | [setStretch(int value)](#setStretch-int-) | 文档页面上的拉伸模式。 |
|
|  | [getRotationAngle()](#getRotationAngle--) | 文档页面上签名的旋转角度（顺时针）。 |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | 文档页面上签名的旋转角度（顺时针）。 |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | 文档页面上签名的水平对齐方式。 |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 文档页面上签名的水平对齐方式。 |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | 文档页面上签名的垂直对齐方式。 |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 文档页面上签名的垂直对齐方式。 |
|
|  | [getMargin()](#getMargin--) | 获取或设置签名与文档边缘之间的间距。 |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | 获取或设置签名与文档边缘之间的间距。 |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | 获取或设置边距的测量类型（像素、百分比或毫米）。 |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | 获取或设置边距的测量类型（像素、百分比或毫米）。 |
|
|  | [getTransparency()](#getTransparency--) | 获取或设置签名透明度（值范围为 0.0（不透明）至 1.0（透明））。 |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 获取或设置签名透明度（值范围为 0.0（不透明）至 1.0（透明））。 |
|
|  | [getText()](#getText--) | 获取或设置签名的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 获取或设置签名的文本。 |
|
|  | [getFont()](#getFont--) | 获取或设置签名的字体。 |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | 获取或设置签名的字体。 |
|
|  | [getForeColor()](#getForeColor--) | 获取或设置签名的前景颜色。 |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | 获取或设置签名的前景颜色。 |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | 获取或设置文本签名实现的类型。 |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | 获取或设置文本签名实现的类型。 |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | 签名内部文本的水平对齐方式。 |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | 签名内部文本的水平对齐方式。 |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | 签名内部文本的垂直对齐方式。 |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | 签名内部文本的垂直对齐方式。 |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | 获取或设置用于放置文本签名的文本表单字段的标题。 |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | 获取或设置用于放置文本签名的文本表单字段的标题。 |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | 获取或设置用于放置文本签名的表单字段的类型。 |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | 获取或设置用于放置文本签名的表单字段的类型。 |
|
|  | [getShapeType()](#getShapeType--) | 获取或设置放置文本的形状类型。 |
|
|  | [setShapeType(int value)](#setShapeType-int-) | 获取或设置放置文本的形状类型。 |
|
|  | [getSignatureID()](#getSignatureID--) | 获取或设置签名的唯一 ID。 |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | 获取或设置签名的唯一 ID。 |
|
|  | [getBorder()](#getBorder--) | 指定边框设置 |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 指定边框设置 |
|
|  | [getBackground()](#getBackground--) | 获取或设置签名的背景设置。 |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | 获取或设置签名的背景设置。 |
|
|  | [getNative()](#getNative--) | 获取或设置本机属性。 |
|
|  | [setNative(boolean value)](#setNative-boolean-) | 获取或设置本机属性。 |
|
|  | [getShapePosition()](#getShapePosition--) | 定义形状在文档布局中的呈现位置 |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | 定义形状在文档布局中的呈现位置 |
|
|  | [validate()](#validate--) | 内部方法，用于验证选项参数。 |
|
|  | [toString()](#toString--) | 覆盖字符串转换。 |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


使用默认值初始化 SignTextOptions 类的新实例。


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


使用文本初始化 SignTextOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 签名文本。 |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


文档页面上签名的左侧 X 位置（以测量值表示）
(像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 属性)。
(如果未指定水平对齐，则有效)。


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


文档页面上签名的左侧 X 位置（以测量值表示）
(像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 属性)。
(如果未指定水平对齐，则有效)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


文档页面上签名的顶部 Y 位置（以测量值表示）
(像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 属性)。
(如果未指定垂直对齐，则有效)。


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


文档页面上签名的顶部 Y 位置（以测量值表示）
(像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 属性)。
(如果未指定垂直对齐，则有效)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


文档页面上签名的宽度（以测量值表示）
（像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 属性）。


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


文档页面上签名的宽度（以测量值表示）
（像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 属性）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


文档页面上签名的高度（以测量值表示）
（像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 属性）。


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


文档页面上签名的高度（以测量值表示）
（像素、百分比或毫米，请参阅 [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 属性）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


左侧和顶部属性的测量类型（像素、百分比或毫米）。


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


左侧和顶部属性的测量类型（像素、百分比或毫米）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


宽度和高度属性的测量类型（像素、百分比或毫米）。


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


宽度和高度属性的测量类型（像素、百分比或毫米）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


文档页面上的拉伸模式。


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


文档页面上的拉伸模式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


文档页面上签名的旋转角度（顺时针）。


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


文档页面上签名的旋转角度（顺时针）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


文档页面上签名的水平对齐方式。


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


文档页面上签名的水平对齐方式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


文档页面上签名的垂直对齐方式。


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


文档页面上签名的垂直对齐方式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


获取或设置签名与文档边缘之间的间距。
(仅在指定水平或垂直对齐时有效)。


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


获取或设置签名与文档边缘之间的间距。
(仅在指定水平或垂直对齐时有效)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


获取或设置边距的测量类型（像素、百分比或毫米）。


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


获取或设置边距的测量类型（像素、百分比或毫米）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


获取或设置签名透明度（值范围从 0.0（不透明）到 1.0（透明））。默认值为 0（不透明）。


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


获取或设置签名透明度（值范围从 0.0（不透明）到 1.0（透明））。默认值为 0（不透明）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getText() {#getText--}
```
public final String getText()
```


获取或设置签名的文本。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


获取或设置签名的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


获取或设置签名的字体。


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


获取或设置签名的字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


获取或设置签名的前景颜色。


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


获取或设置签名的前景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


获取或设置文本签名实现的类型。


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


获取或设置文本签名实现的类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


签名内部文本的水平对齐方式。
此功能仅在图像和注释签名实现中受支持
（请参阅 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation 属性）。


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


签名内部文本的水平对齐方式。
此功能仅在图像和注释签名实现中受支持
（请参阅 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation 属性）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


签名内部文本的垂直对齐方式。
此功能仅在图像签名实现中受支持
（请参阅 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation 属性）。


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


签名内部文本的垂直对齐方式。
此功能仅在图像签名实现中受支持
（请参阅 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation 属性）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


获取或设置用于放置文本签名的文本表单字段的标题。
此属性只能与 SignatureImplementation = TextToFormField 一起使用。


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


获取或设置用于放置文本签名的文本表单字段的标题。
此属性只能与 SignatureImplementation = TextToFormField 一起使用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


获取或设置用于放置文本签名的表单字段的类型。
此属性只能与 SignatureImplementation = TextToFormField 一起使用。
默认值为 AllTextTypes。


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


获取或设置用于放置文本签名的表单字段的类型。
此属性只能与 SignatureImplementation = TextToFormField 一起使用。
默认值为 AllTextTypes。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


获取或设置放置文本的形状类型。
此属性只能与 SignatureImplementation = TextStamp 一起使用。
默认值为 Rectangle。


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


获取或设置放置文本的形状类型。
此属性只能与 SignatureImplementation = TextStamp 一起使用。
默认值为 Rectangle。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


获取或设置签名的唯一 ID。它可用于签名验证选项。此属性仅在 PDF 文档中受支持。


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


获取或设置签名的唯一 ID。它可用于签名验证选项。此属性仅在 PDF 文档中受支持。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


指定边框设置


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


指定边框设置


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


获取或设置签名的背景设置。


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


获取或设置签名的背景设置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


获取或设置本机属性。如果设置了该属性，可使用特定文档的签名。
例如，WordProcessing 文档的本机文本水印不同于常规水印。


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


获取或设置本机属性。如果设置了该属性，可使用特定文档的签名。
例如，WordProcessing 文档的本机文本水印不同于常规水印。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


定义形状在文档布局中的呈现位置


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


定义形状在文档布局中的呈现位置


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### validate() {#validate--}
```
public void validate()
```


内部方法，用于验证选项参数。


### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。


**Returns:**
java.lang.String - 
