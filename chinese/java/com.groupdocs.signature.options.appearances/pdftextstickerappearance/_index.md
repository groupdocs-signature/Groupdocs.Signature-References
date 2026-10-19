---
title: "PdfTextStickerAppearance"
second_title: "GroupDocs.Signature for Java API 参考"
description: "描述 PDF 文本注释贴纸对象及其弹出窗口的外观。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

描述 PDF 文本注释贴纸对象及其弹出窗口的外观。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | 创建 PDF 签名文本注释外观对象。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getTitle()](#getTitle--) | 获取或设置弹出窗口的标题。 |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | 获取或设置弹出窗口的标题。 |
|
|  | [getSubject()](#getSubject--) | 获取或设置主题。 |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | 获取或设置主题。 |
|
|  | [getContents()](#getContents--) | 获取或设置弹出窗口的内容。 |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | 获取或设置弹出窗口的内容。 |
|
|  | [getOpened()](#getOpened--) | 设置是否默认打开贴纸弹出窗口。 |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | 设置是否默认打开贴纸弹出窗口。 |
|
|  | [getIcon()](#getIcon--) | 获取或设置贴纸的图标。 |
|
|  | [setIcon(int value)](#setIcon-int-) | 获取或设置贴纸的图标。 |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | 获取贴纸的默认外观。 |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | 清除贴纸默认外观的值。 |
|
|  | [toString()](#toString--) | 覆盖字符串转换。 |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


创建 PDF 签名文本注释外观对象。


### getTitle() {#getTitle--}
```
public final String getTitle()
```


获取或设置弹出窗口的标题。


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


获取或设置弹出窗口的标题。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


获取或设置主题。


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


获取或设置主题。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


获取或设置弹出窗口的内容。


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


获取或设置弹出窗口的内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


设置是否默认打开贴纸弹出窗口。


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


设置是否默认打开贴纸弹出窗口。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


获取或设置贴纸的图标。


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


获取或设置贴纸的图标。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


获取贴纸的默认外观。如果
未指定 Options.SignatureAppearance 属性。
用户可以随时更改这些属性。


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


清除贴纸默认外观的值。


### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。


**Returns:**
java.lang.String - 
