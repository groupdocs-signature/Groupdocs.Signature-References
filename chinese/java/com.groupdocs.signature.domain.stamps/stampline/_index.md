---
title: "StampLine"
second_title: "GroupDocs.Signature for Java API 参考"
description: "指定印章线属性。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.signature.domain.stamps/stampline/
---
**Inheritance:**
java.lang.Object
```
public class StampLine
```

指定印章线属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [StampLine()](#StampLine--) | 使用默认值创建 StampLine。 |
|
|  | [StampLine(String text)](#StampLine-java.lang.String-) | 使用文本创建 StampLine。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getHeight()](#getHeight--) | 获取或设置 Stamp 上的行高。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 获取或设置 Stamp 上的行高。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 获取或设置签名的背景颜色。 |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | 获取或设置签名的背景颜色。 |
|
|  | [setBackgroundColor(String value)](#setBackgroundColor-java.lang.String-) | 获取或设置签名的背景颜色。 |
|
|  | [getText()](#getText--) | 获取或设置印章行的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 获取或设置印章行的文本。 |
|
|  | [getFont()](#getFont--) | 获取或设置印章行文本的字体。 |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | 获取或设置印章行文本的字体。 |
|
|  | [getTextColor()](#getTextColor--) | 获取或设置签名的文本颜色。 |
|
|  | [setTextColor(Color value)](#setTextColor-java.awt.Color-) | 获取或设置签名的文本颜色。 |
|
|  | [setTextColor(String value)](#setTextColor-java.lang.String-) | 获取或设置签名的文本颜色。 |
|
|  | [getTextBottomIntent()](#getTextBottomIntent--) | 获取或设置文本的底部间距。 |
|
|  | [setTextBottomIntent(int value)](#setTextBottomIntent-int-) | 获取或设置文本的底部间距。 |
|
|  | [getTextRepeatType()](#getTextRepeatType--) | 获取或设置文本重复类型。 |
|
|  | [setTextRepeatType(int value)](#setTextRepeatType-int-) | 获取或设置文本重复类型。 |
|
|  | [getOuterBorder()](#getOuterBorder--) | 设置外部边框。 |
|
|  | [setOuterBorder(Border value)](#setOuterBorder-com.groupdocs.signature.domain.Border-) | 设置外部边框。 |
|
|  | [getInnerBorder()](#getInnerBorder--) | 设置内部边框。 |
|
|  | [setInnerBorder(Border value)](#setInnerBorder-com.groupdocs.signature.domain.Border-) | 设置内部边框。 |
|
|  | [getVisible()](#getVisible--) | 获取和设置 Stamp 行的可见性。 |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | 获取和设置 Stamp 行的可见性。 |
|
### StampLine() {#StampLine--}
```
public StampLine()
```


使用默认值创建 StampLine。


### StampLine(String text) {#StampLine-java.lang.String-}
```
public StampLine(String text)
```


使用文本创建 StampLine。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | Stamp 行的文本。 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取或设置 Stamp 上的行高。


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


获取或设置 Stamp 上的行高。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


获取或设置签名的背景颜色。


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


获取或设置签名的背景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setBackgroundColor(String value) {#setBackgroundColor-java.lang.String-}
```
public final void setBackgroundColor(String value)
```


获取或设置签名的背景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


获取或设置印章行的文本。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


获取或设置印章行的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


获取或设置印章行文本的字体。


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


获取或设置印章行文本的字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getTextColor() {#getTextColor--}
```
public final Color getTextColor()
```


获取或设置签名的文本颜色。


**Returns:**
java.awt.Color
### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public final void setTextColor(Color value)
```


获取或设置签名的文本颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setTextColor(String value) {#setTextColor-java.lang.String-}
```
public final void setTextColor(String value)
```


获取或设置签名的文本颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getTextBottomIntent() {#getTextBottomIntent--}
```
public final int getTextBottomIntent()
```


获取或设置文本的底部间距。


**Returns:**
int
### setTextBottomIntent(int value) {#setTextBottomIntent-int-}
```
public final void setTextBottomIntent(int value)
```


获取或设置文本的底部间距。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTextRepeatType() {#getTextRepeatType--}
```
public final int getTextRepeatType()
```


获取或设置文本重复类型。


**Returns:**
int
### setTextRepeatType(int value) {#setTextRepeatType-int-}
```
public final void setTextRepeatType(int value)
```


获取或设置文本重复类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getOuterBorder() {#getOuterBorder--}
```
public final Border getOuterBorder()
```


设置外部边框。


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setOuterBorder(Border value) {#setOuterBorder-com.groupdocs.signature.domain.Border-}
```
public final void setOuterBorder(Border value)
```


设置外部边框。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getInnerBorder() {#getInnerBorder--}
```
public final Border getInnerBorder()
```


设置内部边框。


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setInnerBorder(Border value) {#setInnerBorder-com.groupdocs.signature.domain.Border-}
```
public final void setInnerBorder(Border value)
```


设置内部边框。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


获取和设置 Stamp 行的可见性。


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


获取和设置 Stamp 行的可见性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

