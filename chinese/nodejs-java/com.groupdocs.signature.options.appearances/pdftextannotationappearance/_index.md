---
title: "PdfTextAnnotationAppearance"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "描述 PDF 文本注释对象的外观 Title Subject Content。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

描述 PDF 文本注释对象（标题、主题、内容）的外观。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | 创建 PDF 签名 txt 注释外观对象。 |
| [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | 使用指定值（title, subject, contents）创建 PDF 签名 txt 注释。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getContents()](#getContents--) | 获取或设置注释对象的内容。 |
| [setContents(String value)](#setContents-java.lang.String-) | 获取或设置注释对象的内容。 |
| [getSubject()](#getSubject--) | 获取或设置表示对象描述的 Subject。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 获取或设置表示对象描述的 Subject。 |
| [getTitle()](#getTitle--) | 获取或设置将在注释对象标题栏中显示的 Title。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 获取或设置将在注释对象标题栏中显示的 Title。 |
| [getBorder()](#getBorder--) | 获取或设置不同的边框设置 |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 获取或设置不同的边框设置 |
| [getBorderEffect()](#getBorderEffect--) | 获取或设置边框效果。 |
| [setBorderEffect(int value)](#setBorderEffect-int-) | 获取或设置边框效果。 |
| [getBorderEffectIntensity()](#getBorderEffectIntensity--) | 获取或设置边框效果强度。 |
| [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | 获取或设置边框效果强度。 |
| [getHCornerRadius()](#getHCornerRadius--) | 获取或设置水平角半径。 |
| [setHCornerRadius(int value)](#setHCornerRadius-int-) | 获取或设置水平角半径。 |
| [getVCornerRadius()](#getVCornerRadius--) | 获取或设置垂直角半径。 |
| [setVCornerRadius(int value)](#setVCornerRadius-int-) | 获取或设置垂直角半径。 |
| [toString()](#toString--) | 覆盖字符串转换。 |
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


创建 PDF 签名 txt 注释外观对象。

### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


使用指定值（title, subject, contents）创建 PDF 签名 txt 注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| title | java.lang.String | 标题。 |
| subject | java.lang.String | 主题。 |
| contents | java.lang.String | 内容。 |

### getContents() {#getContents--}
```
public final String getContents()
```


获取或设置注释对象的内容。

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


获取或设置注释对象的内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


获取或设置表示对象描述的 Subject。

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


获取或设置表示对象描述的 Subject。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


获取或设置将在注释对象标题栏中显示的 Title。

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


获取或设置将在注释对象标题栏中显示的 Title。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


获取或设置不同的边框设置

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


获取或设置不同的边框设置

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


获取或设置边框效果。

**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


获取或设置边框效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


获取或设置边框效果强度。有效值范围为 [0..2]。

**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


获取或设置边框效果强度。有效值范围为 [0..2]。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


获取或设置水平角半径。

**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


获取或设置水平角半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


获取或设置垂直角半径。

**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


获取或设置垂直角半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。

**Returns:**
java.lang.String -
