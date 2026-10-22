---
title: "WordProcessingTextSignatureImplementation"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "指定文字处理文档中文本签名的实现类型。"
type: docs
weight: 36
url: /zh/nodejs-java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

指定文字处理文档中文本签名的实现类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [TextStamp](#TextStamp) | 文本签名作为 Words 页面上的标签对象。 |
| [TextAsImage](#TextAsImage) | 文本签名作为 Words 页面上的图像对象。 |
| [TextToFormField](#TextToFormField) | 文本签名作为指定表单字段中的文本。 |
| [Watermark](#Watermark) | 文本签名作为 Words 页面上的水印。 |
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


文本签名作为 Words 页面上的标签对象。

### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


文本签名作为 Words 页面上的图像对象。

### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


文本签名作为指定表单字段中的文本。使用此实现类型时只能使用 TextSignOptions.Text、TextSignOptions.FormTextFieldTitle 和 TextSignOptions.FormTextFieldType 选项。

### Watermark {#Watermark}
```
public static final int Watermark
```


文本签名作为 Words 页面上的水印。

