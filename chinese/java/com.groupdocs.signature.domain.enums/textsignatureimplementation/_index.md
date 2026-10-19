---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature for Java API 参考"
description: "指定 PDF 文本签名的实现类型。"
type: docs
weight: 32
url: /zh/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

指定 PDF 文本签名的实现类型。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Native](#Native) | 文本签名作为文档页面上的本机文本对象。 |
|
|  | [Image](#Image) | 文本签名作为文档页面上的图像对象。 |
|
|  | [Annotation](#Annotation) | 文本签名作为 PDF 页面上的文本注释对象。 |
|
|  | [Sticker](#Sticker) | 文本签名作为 PDF 页面上的贴纸对象。 |
|
|  | [FormField](#FormField) | 文本签名作为指定表单字段中的文本。 |
|
|  | [Watermark](#Watermark) | 文本签名作为文档页面上的水印。 |
|
### Native {#Native}
```
public static final int Native
```


文本签名作为文档页面上的本机文本对象。


### Image {#Image}
```
public static final int Image
```


文本签名作为文档页面上的图像对象。


### Annotation {#Annotation}
```
public static final int Annotation
```


文本签名作为 PDF 页面上的文本注释对象。
注释仅在授权版本中可见。


### Sticker {#Sticker}
```
public static final int Sticker
```


文本签名作为 PDF 页面上的贴纸对象。


### FormField {#FormField}
```
public static final int FormField
```


文本签名作为指定表单字段中的文本。
使用此类型的实现只能使用 TextSignOptions.Text，
TextSignOptions.FormTextFieldType 和 TextSignOptions.FormTextFieldTitle 选项。


### Watermark {#Watermark}
```
public static final int Watermark
```


文本签名作为文档页面上的水印。


