---
title: "FormFieldSignOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示 PDF 文档的 FormField 签名选项类。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

表示 PDF 文档的 FormField 签名选项类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FormFieldSignOptions()](#FormFieldSignOptions--) | 使用默认值初始化 PdfFormFieldSignOptions 类的新实例。 |
|
|  | [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | 使用 FormField 签名初始化 PdfFormFieldSignOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSignature()](#getSignature--) | 获取或设置签名的 FormField。 |
|
|  | [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | 获取或设置签名的 FormField。 |
|
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


使用默认值初始化 PdfFormFieldSignOptions 类的新实例。


### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


使用 FormField 签名初始化 PdfFormFieldSignOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


获取或设置签名的 FormField。


**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


获取或设置签名的 FormField。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

