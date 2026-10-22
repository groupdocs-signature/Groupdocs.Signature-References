---
title: "PdfDigitalSignatureAppearance"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "描述 PDF 文档中数字签名的外观。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

描述 PDF 文档中数字签名的外观。

--------------------

**Learn more**

 *  See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures][]
 *  See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties][]


[Advanced signing document with Digital electronic signatures]: https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/
[Advanced electronic signatures properties]: https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | 创建具有默认值的签名外观对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getContactInfoLabel()](#getContactInfoLabel--) | 获取或设置联系信息标签。 |
| [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | 获取或设置联系信息标签。 |
| [getReasonLabel()](#getReasonLabel--) | 获取或设置原因标签。 |
| [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | 获取或设置原因标签。 |
| [getLocationLabel()](#getLocationLabel--) | 获取或设置位置标签。 |
| [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | 获取或设置位置标签。 |
| [getDigitalSignedLabel()](#getDigitalSignedLabel--) | 获取或设置数字签名标签。 |
| [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | 获取或设置数字签名标签。 |
| [getDateSignedAtLabel()](#getDateSignedAtLabel--) | 获取或设置签署日期标签。 |
| [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | 获取或设置签署日期标签。 |
| [getBackground()](#getBackground--) | 获取或设置签名外观的背景颜色。 |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | 获取或设置签名外观的背景颜色。 |
| [setBackground(String value)](#setBackground-java.lang.String-) | 获取或设置签名外观的背景颜色。 |
| [getFontFamilyName()](#getFontFamilyName--) | 获取或设置用于显示标签的字体系列名称。 |
| [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | 获取或设置用于显示标签的字体系列名称。 |
| [getFontSize()](#getFontSize--) | 获取或设置用于显示标签的字体大小。 |
| [setFontSize(double value)](#setFontSize-double-) | 获取或设置用于显示标签的字体大小。 |
| [getForeground()](#getForeground--) | 获取或设置签名外观的前景文字颜色。 |
| [setForeground(Color value)](#setForeground-java.awt.Color-) | 获取或设置签名外观的前景文字颜色。 |
| [setForeground(String value)](#setForeground-java.lang.String-) | 获取或设置签名外观的前景文字颜色。 |
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


创建具有默认值的签名外观对象。

### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


获取或设置联系信息标签。默认值：\"Contact\"。如果此值为空，则数字签名区域不会出现联系标签。

**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


获取或设置联系信息标签。默认值：\"Contact\"。如果此值为空，则数字签名区域不会出现联系标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


获取或设置原因标签。默认值：\"Reason\"。如果此值为空，则数字签名区域不会出现原因标签。

**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


获取或设置原因标签。默认值：\"Reason\"。如果此值为空，则数字签名区域不会出现原因标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


获取或设置位置标签。默认值：\"Location\"。如果此值为空，则数字签名区域不会出现位置标签。

**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


获取或设置位置标签。默认值：\"Location\"。如果此值为空，则数字签名区域不会出现位置标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


获取或设置数字签名标签。默认值：\"Digitally signed by\"。

**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


获取或设置数字签名标签。默认值：\"Digitally signed by\"。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


获取或设置已签署日期标签。默认值: "Date".

**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


获取或设置已签署日期标签。默认值: "Date".

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


获取或设置签名外观的背景颜色。默认情况下该值为 SystemColors.Windows

**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


获取或设置签名外观的背景颜色。默认情况下该值为 SystemColors.Windows

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


获取或设置签名外观的背景颜色。默认情况下该值为 SystemColors.Windows

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


获取或设置用于显示标签的字体系列名称。默认值为 "Arial".

**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


获取或设置用于显示标签的字体系列名称。默认值为 "Arial".

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


获取或设置用于显示标签的字体大小。默认值为 10.

**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


获取或设置用于显示标签的字体大小。默认值为 10.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


获取或设置签名外观的前景文本颜色。默认情况下该值为 Color.FromArgb(76, 100, 255)

**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


获取或设置签名外观的前景文本颜色。默认情况下该值为 Color.FromArgb(76, 100, 255)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


获取或设置签名外观的前景文本颜色。默认情况下该值为 Color.FromArgb(76, 100, 255)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

