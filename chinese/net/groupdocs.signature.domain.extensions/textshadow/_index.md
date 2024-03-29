---
title: TextShadow
second_title: GroupDocs.Signature for .NET API 参考
description: 表示文本签名的文本阴影属性 结果可能因签名类型和文档格式而异 TextShadow 建议与所有支持的文档类型的 TextAsImage 签名一起使用 也与简单的 TextSignature 和 TextSignature 作为电子表格的水印一起使用 .xslx 和演示文稿 .pptx. Simple TextSignature for Words .docx 也被推荐但功能有限.
type: docs
weight: 400
url: /zh/net/groupdocs.signature.domain.extensions/textshadow/
---
## TextShadow class

表示文本签名的文本阴影属性。 结果可能因签名类型和文档格式而异。 TextShadow 建议与所有支持的文档类型的 TextAsImage 签名一起使用， 也与简单的 TextSignature 和 TextSignature 作为电子表格的水印一起使用（ .xslx) 和演示文稿 (.pptx). Simple TextSignature for Words (.docx) 也被推荐，但功能有限.

```csharp
public class TextShadow : SignatureExtension
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TextShadow](textshadow)() | 使用默认选项创建 TextShadow。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Angle](../../groupdocs.signature.domain.extensions/textshadow/angle) { get; set; } | 获取或设置放置阴影相对于文本的角度。 默认值为 0. |
| [Blur](../../groupdocs.signature.domain.extensions/textshadow/blur) { get; set; } | 获取或设置阴影的模糊度。 默认值为 4. |
| [Color](../../groupdocs.signature.domain.extensions/textshadow/color) { get; set; } | 获取或设置阴影的颜色。 默认值为黑色。 |
| [Distance](../../groupdocs.signature.domain.extensions/textshadow/distance) { get; set; } | 获取或设置从文本到阴影的距离。 默认值为 1. |
| [Transparency](../../groupdocs.signature.domain.extensions/textshadow/transparency) { get; set; } | 获取或设置阴影的透明度。 默认值为 0. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain.extensions/signatureextension/clone)() | 获取此对象的副本。 |

### 也可以看看

* class [SignatureExtension](../signatureextension)
* 命名空间 [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
